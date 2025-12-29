# Data Model: Physical AI & Humanoid Robotics Course

## Course Module
- **name**: string (e.g., "The Robotic Nervous System (ROS 2)")
- **description**: string (module focus and objectives)
- **chapters**: array of Chapter objects
- **order**: integer (sequence of module in course)

### Relationships
- Contains many Chapter objects

## Chapter
- **title**: string (chapter name)
- **content**: string (Markdown content)
- **module**: Module object (parent module)
- **order**: integer (sequence of chapter in module)
- **learning_objectives**: array of strings
- **prerequisites**: array of strings (required knowledge)

### Relationships
- Belongs to one Module object
- Contains many ContentSection objects

## ContentSection
- **title**: string (section header)
- **content**: string (Markdown content)
- **chapter**: Chapter object (parent chapter)
- **order**: integer (sequence in chapter)

### Relationships
- Belongs to one Chapter object

## Student
- **id**: string (unique identifier)
- **name**: string (student name)
- **progress**: array of Progress objects
- **enrollment_date**: date

### Relationships
- Has many Progress objects

## Progress
- **student**: Student object
- **chapter**: Chapter object
- **completed**: boolean
- **completion_date**: date (optional)
- **assessment_score**: number (optional)

### Relationships
- Links Student and Chapter objects

## Assessment
- **title**: string (assessment name)
- **chapter**: Chapter object (associated chapter)
- **questions**: array of Question objects
- **passing_score**: number (minimum required)

### Relationships
- Belongs to one Chapter object
- Contains many Question objects

## Question
- **text**: string (question content)
- **type**: string (multiple-choice, short-answer, practical)
- **options**: array of strings (for multiple-choice)
- **correct_answer**: string or array (correct response)
- **assessment**: Assessment object (parent assessment)

### Relationships
- Belongs to one Assessment object