# Welcome to My Profile, I'm Younes ! 👋
If you love the code, it will love you back
## About Me

```python
class AboutMe:
    def __init__(self, full_name, role, bio, education, soft_skills):
        self.full_name = full_name
        self.role = role
        self.bio = bio
        self.education = education
        self.soft_skills = soft_skills

    def __str__(self):
        info = f"Hi, I'm {self.full_name}, a {self.role}.\n\n"
        info += f"**Bio:** {self.bio}\n\n"
        info += f"**Education:** {self.education}\n\n"
        info += f"**Additional Skills:** {', '.join(self.additional_skills)}\n\n"
        return info

# Create an instance of the AboutMe class
about_me = AboutMe(
    full_name="Younes Sghyer",
    role="Python Developer",
    bio="Passionate about Backend api development and data science.",
    education=["Self Taught", "Bachelor degree in IT Systems Engineering", "Currently Student in master degree of science in IT"],
)

print(about_me)
