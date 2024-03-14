# Welcome to Younes202's Profile! 👋

## About Me

```python
class AboutMe:
    def __init__(self, name, role, bio, interests, philosophy, study, education, work_experience, additional_skills):
        self.name = name
        self.role = role
        self.bio = bio
        self.interests = interests
        self.philosophy = philosophy
        self.study = study
        self.education = education
        self.work_experience = work_experience
        self.additional_skills = additional_skills

    def __str__(self):
        info = f"Hi, I'm {self.name}, a {self.role}.\n\n"
        info += f"**Bio:** {self.bio}\n\n"
        info += f"**Interests:** {', '.join(self.interests)}\n\n"
        info += f"**Philosophy:** {self.philosophy}\n\n"
        info += f"**Study:** {self.study}\n\n"
        info += f"**Education:** {self.education}\n\n"
        info += f"**Work Experience:** {self.work_experience}\n\n"
        info += f"**Additional Skills:** {', '.join(self.additional_skills)}\n\n"
        return info

# Create an instance of the AboutMe class
about_me = AboutMe(
    name="Younes202",
    role="Python Developer",
    bio="Passionate about building web applications with FastAPI. I love exploring new technologies and sharing my knowledge with others.",
    interests=["API development", "Backend architecture", "Cloud computing"],
    philosophy="Continuous learning and improvement are my guiding principles.",
    study="Currently focusing on mastering backend development with Python and FastAPI.",
    education="Bachelor's degree in Computer Science",
    work_experience="2 years of experience in web development with Python and Flask.",
    additional_skills=["Docker", "Git", "RESTful APIs"]
)

print(about_me)
