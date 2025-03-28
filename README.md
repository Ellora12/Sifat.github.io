\documentclass[a4paper,10pt]{article}
\usepackage[a4paper,margin=0.75in]{geometry}
\usepackage{xcolor}
\usepackage{titlesec}
\usepackage{enumitem}
\usepackage{hyperref}

% Colors and Formatting
\definecolor{darkblue}{RGB}{25, 25, 112}
\definecolor{graytext}{RGB}{100, 100, 100}
\definecolor{accent}{RGB}{0, 153, 204}
\titleformat{\section}{\large\bfseries\color{darkblue}}{}{0em}{}[\titlerule]

\begin{document}

% Header
\begin{center}
    {\LARGE \textbf{Your Name}} \\ [1mm]
    \color{graytext}\texttt{your.email@example.com} $|$ \texttt{linkedin.com/in/yourprofile} $|$ \texttt{github.com/yourgithub}
\end{center}

\vspace{5mm}

% Technical Skills
\section*{Technical Skills}
\textbf{Languages:} Python, SQL, MATLAB  \\
\textbf{Tools:} AWS, Snowflake, TensorFlow, Scikit-Learn

% Education
\section*{Education}
\textbf{Ph.D. in Physics}, The University of Texas at Dallas \hfill \textit{May 2022}\\
\textbf{M.S. in Physics}, The University of Texas at Dallas \hfill \textit{Dec 2019}\\
\textbf{B.S. in Physics}, The University of Texas at Dallas \hfill \textit{May 2017}

% Work Experience
\section*{Work Experience}
\textbf{Data Scientist}, Toyota Financial Services \hfill \textit{June 2022 - Present}\\
\begin{itemize}[noitemsep, topsep=0pt]
    \item Optimized loan origination models, reducing potential losses by $\sim$1M.
    \item Enhanced production data pipeline, improving coverage for 70\% of accounts.
\end{itemize}

\textbf{Data Science Consultant}, Shawhin Talebi Ventures LLC \hfill \textit{Dec 2020 - Present}\\
\begin{itemize}[noitemsep, topsep=0pt]
    \item Developed deep learning models to analyze 300+ biometric variables in live-fire training.
    \item Discovered novel sepsis sub-phenotypes using unsupervised learning on ICU data.
\end{itemize}

% Projects
\section*{Projects}
\textbf{EEG Band Discovery with Decision Trees} \hfill \textit{Python}\\
Developed an automated approach to define EEG bands that outperform standard definitions. [\href{https://www.mdpi.com/1424-8220/22/8/3048}{Publication}]

\textbf{Machine Learning for Airborne Sensor Calibration} \hfill \textit{MATLAB}\\
Trained 100+ ML models estimating particulate matter based on biometric data. Achieved $r^2=0.91$. [\href{https://www.mdpi.com/1424-8220/22/11/4240}{Publication}]

% Publications
\section*{Publications}
1. Talebi S., Lary D.J. \textit{et al.}, Machine Learning for Pupillary Response Modeling (2019). 
2. Wijeratne, L.O. \textit{et al.}, Airborne Sensor Calibration with ML, Sensors 2020.

% Talks & Lectures
\section*{Talks & Lectures}
\begin{itemize}[noitemsep, topsep=0pt]
    \item Guest Lecture: Dimensionality Reduction - PHYS 5336, Spring 2021
    \item Causality and Machine Learning - GSP Seminar, Fall 2021
\end{itemize}

\vfill
\centering{\color{graytext}\textit{Last Updated: March 2025}}

\end{document}
