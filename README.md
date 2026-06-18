# Shorelands British Academy — Digital Skills Program

Welcome to the official GitHub organization for the Shorelands Digital Skills Program. This is where students push their assignments and project work for the duration of the program.

Powered in partnership with **D'Creativs**.

## Tracks

- **Web Development** (HTML & CSS) — led by Xant
- **3D / Blender** — led by Kingsley

## Classes

Students are grouped by class:

- **J1** — Junior 1
- **J2** — Junior 2
- **S1** — Senior 1
- **S2** — Senior 2

Each class has its own Team on this organization. Your facilitator will add you to your class team, which gives you and your classmates access to relevant repos.

## Getting Started

### 1. Create your repository on GitHub

1. Create a new repository using this naming format: `shorelands-[class]-[track]-[yourname]`
   Example: `shorelands-j1-webdev-johndoe` or `shorelands-s2-blender-janedoe`
2. Set the repository to **private**.
3. Add your class team (e.g. `J1`) as a collaborator with **Write** access.

### 2. Set up your local folder

Open your terminal and run:

```
mkdir yourname
cd yourname
git init
mkdir assignment class
```

This creates two folders: `assignment` for your assignment work, and `class` for in-class exercises or notes.

### 3. Connect your local folder to your GitHub repo

```
git remote add origin https://github.com/Shorelands-British-Academy/shorelands-[class]-[track]-yourname.git
```

You'll find this exact URL on your repo page under the green **Code** button.

### 4. Push your first commit

```
git add .
git commit -m "Initial setup with assignment and class folders"
git branch -M main
git push -u origin main
```

### 5. Future updates

Every time you add new work, run:

```
git add .
git commit -m "Describe what you added, e.g. Week 2 assignment"
git push
```

## Submission Rules

- Each assignment should be pushed as a separate, clearly labeled folder or commit (e.g. `week1-assignment`, `week2-project`).
- Include a short `README.md` inside your repo describing what each project does, if it's not obvious from the code or files.
- Do not force-push or delete previous submissions. We track your progress over the full program.
- Submissions are due by the deadline shared in class. Late pushes will be timestamped automatically by GitHub, so there's no need to message anyone for confirmation.

## Need Help?

If you're stuck on Git or GitHub basics (cloning, committing, pushing), ask your facilitator during class or reach out through the program's communication channel.

---

*Built to be noticed — D'Creativs*
