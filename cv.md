# Alex Romanova

Software Engineering Student

## About Me

Motivated software engineering student with a interest in web development and backend systems. I am eager to learn new technologies, improve my programming skills, and work on real-world
projects. Responsible, detail-oriented and a fast learner.

## Skills

Languages: C#, JavaScript, HTML, CSS
Frameworks: .NET
Version Control: Git, GitHub  
 Tools: VS Code, Visual Studio, Git Bash

## Code Example

static double FuzzyMatch(string search, string target, double threshold = 0.3)
{
search = search.ToLower();
target = target.ToLower();
if (target.Contains(search))
return 1;
if (search.Length &lt;= 3 && target.EndsWith(search))
return 1;
double ngramSim = NGramSimilarity(search, target, 2);
if (ngramSim >= threshold)
return ngramSim;
return 0;
}

static double NGramSimilarity(string s1, string s2, int n = 2)
{
var ngrams1 = Enumerable.Range(0, s1.Length - n + 1).Select(i => s1.Substring(i, n));
var ngrams2 = Enumerable.Range(0, s2.Length - n + 1).Select(i => s2.Substring(i, n));
var common = ngrams1.Intersect(ngrams2).Count();
return (double)common / Math.Max(ngrams1.Count(), ngrams2.Count());
}

## Projects

Student Assistant Web App – Attendance tracking system. Skills used: HTML, CSS, JavaScript, backend integration. https://github.com/AlexRomanova/Group-monitor.git
Personal CV Website – CV page https://github.com/AlexRomanova/WebProgramming.git

## Courses & Training

HTML ans CSS
JavaScript for beginers
C# programming
Web Development Basics
Object-Oriented Programming
Git & GitHub Course
Data Bases

## English Level

Intermediate (B1–B2). Practiced English through real lifeconversations, Youtube content and technical documentation.

## Contacts

Email: romanova.aleksandra943@gmail.com  
GitHub: https://github.com/AlexRomanova
