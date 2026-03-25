# Data Entities

## 1. User
- id
- name
- email
- password
- major
- graduationYear

## 2. Application
- id
- jobTitle
- companyName
- status
- deadline
- applicationLink
- notes
- userId

## 3. SkillGoal
- id
- skillName
- targetLevel
- progressPercent
- deadline
- userId

## Relationships
- One User can have many Applications
- One User can have many SkillGoals
- Opportunities from the external API can be saved as Applications
