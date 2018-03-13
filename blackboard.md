https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.linprog.html
http://lpsolve.sourceforge.net/5.5/Python.htm

https://github.com/JWally/jsLPSolver

1) Definire le variabili, tutte binarie, ognuna corrispondente a un'associazione (Veicolo, Ride);
2) Veicoli e Ride hanno un indice stabilito dal file di input, che dobbiamo mantenere e che andrà
stampato nel file di output (ricordo che il formato è: ogni riga, a partire da 0, rappresenta un Veicolo
  e i caratteri da stampare sono (#rideAssegnate, indiciRidesAssegnate . . .))
3)


> from lpsolve55 import *
> lpsolve()
