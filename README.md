## Hi there 👋

<div id="header" align="center">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXd2dDgxcnI2cjNtcHllcG1rdWY1MG5uY2VzNTl4d2J1M3o3cnc2MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/bGgsc5mWoryfgKBx1u/giphy.gif" width="100"/>
  <div id="badges">
  <a href="https://www.linkedin.com/in/dmitrii-meshkov-dev/" rel="nofollow"><img src="https://camo.githubusercontent.com/e1a5bef50eb40eda6dbc1095c42128665a9452f9577a905ddc3be24292b7ac72/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c696e6b6564696e2d3030373742353f7374796c653d666c61742d737175617265266c6f676f3d6c696e6b6564696e266c6f676f436f6c6f723d7768697465" alt="Linkedln" data-canonical-src="https://img.shields.io/badge/linkedin-0077B5?style=flat-square&amp;logo=linkedin&amp;logoColor=white" style="max-width: 100%;"></a>
</div>
</div>

```
final class MyProfile
{
    public function show(): void
    {
        $profile = new DeveloperProfile([
            'name' => '🧑‍💻 Dmitrii Meshkov',
            'location' => '📍 Toronto, Canada',
            'role' => '💼 Full-Stack Web Developer',
            'experience' => '📅 5+ years of experience in building and maintaining web applications',
            'skills' => [
                'Frontend Development' => ['⚛️ React', '🔄 Redux', '⚡ Vite', '📜 JavaScript', '⌨️ TypeScript'],
                'Backend Development' => ['🐘 PHP', '🌐 Laravel', '🐍 Python', '🧩 Django'],
                'Databases' => ['🐘 PostgreSQL', '🐬 MySQL', '💽 MSSQL'],
                'DevOps & Tools' => ['🚀 GitLab CI/CD', '🐳 Docker', '☁️ Azure', '🔐 LDAP', '🏢 Active Directory'],
                'Automation & Scripting' => ['📜 PowerShell', '🐚 Bash'],
            ],
            'softSkills' => ['🧩 Problem Solving', '🤝 Team Collaboration', '🔄 Adaptability', '🚀 Efficiency Optimization'],
        ]);
        echo json_encode($profile, JSON_PRETTY_PRINT);
    }
}

```
<!--
**Takechico/Takechico** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
