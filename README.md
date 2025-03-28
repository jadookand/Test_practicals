%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    \textbf{\Huge \scshape Vivekkumar Pawase} \\ \vspace{1pt}
    \small (+91)9175131272 $|$ {pawasevivek212@gmail.com} $|$ 
    \href{https://linkedin.com/in/...}{Linkedin: vivekkumar-pawase} $|$
    \href{https://github.com/...}{Github: pawase99}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {National Institute of Technology, Rourkela}{06/2018 - 05/2020}
      {M. Tech. in Electrical Engineering, Minor in Power Electronics}{Rourkela, IN}
    \resumeSubheading
      {Pune Vidyarthi Griha's College of Engineering and Technology, Pune}{06/2013 - 05/2017}
      {B.E. in Electrical Engineering}{Pune, IN}
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Bharti Airtel}{01/2023 - Present}
      {Software Engineer}{Pune, IN}
      \resumeItemListStart
        \resumeItem{Led 50M+ users data migration, project planning and Java object development. Proficient in Handlebars and skillful at crafting complex PL/SQL packages, procedures, triggers and SQL queries for Kenan FX Billing and payments collection system.}
        \resumeItem{Optimized complex SQL queries improving database retrieval speed by 40\% and reduced server load costs by 25\%.}
        \resumeItem{Defined project scope, requirements and timelines with product and engineering teams; documented scope on Confluence, enhancing project tracking and teams collaboration, resulting in a 25\% reduction in project delays.}
        
        \resumeItem{Contributed to pipeline creation and played a pivotal role in resolving critical production issues.}
        \resumeItem{Demonstrates strong organizational skills and adeptness at prioritizing tasks to ensure timely project delivery.}
      \resumeItemListEnd
      
% -----------Multiple Positions Heading-----------
%    \resumeSubSubheading
%     {Software Engineer I}{Oct 2014 - Sep 2016}
%     \resumeItemListStart
%        \resumeItem{Apache Beam}
%          {Apache Beam is a unified model for defining both batch and streaming data-parallel processing pipelines}
%     \resumeItemListEnd
%    \resumeSubHeadingListEnd
%-------------------------------------------

    \resumeSubheading
      {Oracle Financial Services Software}{09/2020 - 01/2023}
      {Associate Consultant}{Bangalore, IN}
      \resumeItemListStart
        \resumeItem{Acquired extensive development and implementation expertise in Oracle Flexcube and Oracle EBS, utilizing SQL/PL-SQL and Python in an Agile environment for 5 different clusters of EMEA region.}
        \resumeItem{Proficient in UNIX/Linux Shell Scripting and markup languages including XML and JSON.}
        \resumeItem{Demonstrated strong understanding of Oracle Cloud Infrastructure (OCI) with an 88\% score on the Foundations Associate exam. Collaborated with technical teams, managers, and stakeholders on functional specifications, user requirements, UAT, and production releases across EMEA clusters.}
        \resumeItem{Executed comprehensive code reviews and rigorous software testing, pinpointing and rectifying critical bugs, which enhanced system performance by 40\% and reduced downtime by 25\% within six months.}
        \resumeItem{Strong communication and interpersonal skills with the ability to thrive in fast-paced, research-oriented environments, both independently and collaboratively.}
    \resumeItemListEnd
  \resumeSubHeadingListEnd


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Airtel – Exposure Monitoring Technique} $|$ \emph{PL-SQL, SQL, Java}}{01/2024 - Present}
          \resumeItemListStart
            \resumeItem{Consolidated Six PL/SQL procedures into a single procedure, resulting in a 50\% reduction in job execution time.}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Airtel – Inform Module - DTH PDF generation} $|$ \emph{React JS, Handlebars, MongoDB}}{11/2023 - 01/2024}
          \resumeItemListStart
            \resumeItem{Created a PDF template showcasing the utilization of customer bills for B2C customers, serving a user base of 35 million.}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Airtel – BSL Module - API Onboarding portal} $|$ \emph{Python, HTML/CSS, JS, Oracle DB}}{01/2023 - 11/2023}
          \resumeItemListStart
            \resumeItem{Created a full-stack web application tailored for 100+ APIs onboarding, leveraging Flask for web application, React for the front-end, and Oracle Database for data storage, facilitating developers in tracking API utilization.}
          \resumeItemListEnd    
      \resumeProjectHeading
          {\textbf{Oracle - Citi Bank - Withholdings Tax Calculation } $|$ \emph{PL-SQL, SQL, Oracle Forms}}{02/2022 - 01/2023 }
          \resumeItemListStart
            \resumeItem{Developed tax calculation process on the interest credited to savings accounts and cross-border payments for 10,000+ customers.}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Oracle - Citi Bank - Exception Queue Module} $|$ \emph{PL-SQL, SQL, Oracle Forms, Git}}{01/2021 - 02/2022 }
          \resumeItemListStart
            \resumeItem{Deployed account balance tracking and order freezing functionalities for 5 clusters of EMEA region customers, utilizing PL/SQL packages and queries.}
          \resumeItemListEnd  
    \resumeSubHeadingListEnd

%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: PL-SQL, Python, SQL (Oracle), JavaScript, HTML/CSS} \\
     \textbf{Frameworks}{: React, Flask, RestAPI} \\
     \textbf{Developer Tools}{: Git, Atlassian JIRA, Bitbucket, Postman, Oracle Cloud Infrastructure(OCI), VS Code, IntelliJ} \\
     \textbf{Libraries}{: Flask, Pandas, NumPy, Matplotlib}
    }}
 \end{itemize}


%-------------------------------------------
\end{document}
