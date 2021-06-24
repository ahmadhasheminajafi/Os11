# Os11
بخش اول


بخش دوم

\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{graphicx}
\title{Os11}
\author{Ahmad Hashemi Najafi}
\date{June 2021}

\begin{document}

\maketitle

\section{Introduction}
Hi i'm Ahmad from iran \\
student in computer engineering 
and like game and electronic
\section{picture}
\includegraphics{photo_2020-01-19_14-55-56.png}
\section{table}
\begin{center}
 \begin{tabular}{||c c c c||} 
 \hline
 Col1 & Col2 & Col2 & Col3 \\ [0.5ex] 
 \hline\hline
 1 & 6 & 87837 & 787 \\ 
 \hline
 2 & 7 & 78 & 5415 \\
 \hline
 3 & 545 & 778 & 7507 \\
 \hline
 4 & 545 & 18744 & 7560 \\
 \hline
 5 & 88 & 788 & 6344 \\ [1ex] 
 \hline
\end{tabular}
\end{center}
\section{math}
The mass-energy equivalence is described by the famous equation

\[E=mc^2\]

discovered in 1905 by Albert Einstein. 
In natural units ($c$ = 1), the formula expresses the identity

\begin{equation}
E=m

\end{equation}
\section{code}


int main()\\
{\\
	int a, b,c;\\
	cin >> a >> b;\\
	cout << "gozine ro vared konid" << endl;\\
	cout << "gozine 1 jam " << endl;\\
	cout << "gozine 2 tafrigh konid" << endl;\\
	cout << "gozine 3 baghi mande va kharej ghesmat" << endl;\\
	cout << "gozine 4  zarb" << endl;\\
	cout << "gozine 5 hame mavared  " << endl;\\

	cin >> c;\\
	switch (c)\\
	{\\
	case 1:\\
	{\\
		cout << a + b << endl;\\
		break;\\
	}\\
	case 2:\\
	{\\
		cout << a - b << endl;
		break;\\
	}\\
	case 3:\\
	{\\
		cout << a%b<< endl;\\
		cout << a/b << endl;\\
		break;\\
	}\\
	case 4:\\
	{\\
		cout << a * b << endl;\\
		break;\\
	}\\
	case 5:\\
	{\\
		cout << a + b << endl;\\
		cout << a - b << endl;\\
		cout << a % b << endl;\\
		cout << a / b << endl;\\
		cout << a * b << endl;\\
		break;\\
	}\\
	default:\\
		cout << "adad vared shode eshtebah mibashad";\\
		break;\\
	}\\
}\\
	

\end{document}
