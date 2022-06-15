# Skill Enhancement Buddy
- Mobile-based learning platform covering a wide range of topics (both NS-specific and general)
  - These courses can range in field such as:
    - Soldiering basics (BMT)
    - Vocation-specific courses (with access control)
    - Academic courses such as A-level subjects/coding
    - Life skills such as health and fitness
- Completion of courses officially recognised via publicly verifiable digital badges
- Badges can be showcased on platforms such as LinkedIn
- There are 3 components to this product: a mobile app, verifier web service, and an admin website.


## Mobile App
https://github.com/codeexp22-seb/SEB-iOS
- Learners can explore courses and complete quizzes to earn badges
- Progress Rings to motivate users to work on improving a variety of skills. 
  - Learners will earn points upon completion of a ring
  - These points will allow them to purchase “scratch cards” which can yield prizes such as e-mart credits
  - Learners can close their rings by completing chapters and quizzes within courses
- Upon completion of a course and an assessment quiz, learners will earn a badge which they can share with others, or use as part of their portfolio.


## Badge Verification Website
https://github.com/codeexp22-seb/SEBadge
- Each badge earned after the completion of courses has a unique ID
- This ID can be used to check the validity of the badge 
- The SEBadge web service provides a platform for those interested in verifying the authenticity of a badge 
- Badges can be shared on other platforms and be used as proof of learning on their portfolio for career progression


## Admin Web Panel
https://github.com/codeexp22-seb/SEBadmin
- Design for leaders of organisational units (e.g sergeants of a platoon etc.) 
- Provides an overview of learners and course statistics (e.g. points earned, completion rates)
- **Enhanced diagnostics**: Can be used to monitor progress of learners
- **Access Control**: Can be used to assign courses to certain groups
