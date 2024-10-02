To create a list, there are different methods. 

* One method is using {itemize}:
```
\begin{itemize}
  \item List entries start with the \verb|\item| command.
  \item Individual entries are indicated with a black dot, a so-called bullet.
  \item The text in the entries may be of any length.
\end{itemize}
```
The output is: 
> • List entries start with the \item command.
> • Individual entries are indicated with a black dot, a so-called bullet.
> • The text in the entries may be of any length.





* Another method is using {enumerate}:
```
\begin{enumerate}
  \item Items are numbered automatically.
  \item The numbers start at 1 with each use of the \texttt{enumerate} environment.
  \item Another entry in the list
\end{enumerate}
```

The output of that is:
> 1. Items are numbered automatically.
> 2. The numbers start at 1 with each use of the enumerate environment.
> 3. Another entry in the list
