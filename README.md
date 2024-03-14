# Welcome to My Profile, I'm Younes ! 👋
![Typing SVG](https://readme-typing-svg.herokuapp.com?center=true&vCenter=true&size=30&width=600&height=40&lines=Welcome+to+My+Profile,+I'm+Younes+!+👋)
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

about_me = AboutMe(
    full_name="Younes Sghyer",
    role="Python Developer",
    bio="Passionate about Backend api development and data science.",
    education=["Self Taught", "Bachelor degree in IT Systems Engineering", "Current Student in master degree IT"]
)

print(about_me)
