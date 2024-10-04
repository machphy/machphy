<h1 align="center"><a href="">About Me</a></h1>

```python
class Life(Creativity):
    def __init__(self):
        self.name = "Rajeev Sharma"
        self.current_job_title = "ML Intern"  

    def current_projects(self):
        self.currently_learning = "Engineering📚"
        self.currently_working_on = "On_my_Projects 🌱"
        self.excited_for = "Site Reliability Engineering"
        return {
            "Currently Learning": self.currently_learning,
            "Working On": self.currently_working_on,
            "Excited For": self.excited_for
        }
    
    def contact_me(self):
        self.email = "rajeevsharmamachphy@gmail.com"
        return f"Feel free to reach out via email: {self.email}"
        
    def star_it(self, repo):
        if repo.is_useful():
            return "⭐"
     
    def fork_it(self, repo):
        if repo.is_useful():
            return "🍴"
 
if __name__ == "__main__":
    my_life = Life()
    print(my_life.current_projects())
    print(my_life.contact_me())
    
    repo = SomeRepository() 
    if repo.is_useful():
        print(my_life.star_it(https://github.com/machphy/Real-Time-Cyber-Incident-Monitoring-and-Analysis-Tool.git))
        print(my_life.fork_it(https://github.com/machphy/TubeMetrics-Advanced-Analysis-for-YouTube-Channels.git))

```

![Rajeev's GitHub stats](https://github-readme-stats.vercel.app/api?username=Machphy&count_private=true&show_icons=true&bg_color=00000000)








