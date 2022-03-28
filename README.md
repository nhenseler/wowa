# Package WOWA 
Used for calculating weighted OWA functions and extending bivariate means.

## C++ interface
double OWA(int n, double x[],double w[]);
double OWASorted(int n, double x[],double w[]);
double weightedf(double x[], double p[], double w[], int n,
double(*F)(int, double[],double[]), int L);
void weightedOWAQuantifierBuild( double p[], double w[], int n, double temp[], int& T);
double weightedOWAQuantifier(double x[], double p[], double w[], int n, double temp[], int T);		 
double WAn(double * x, double * w, int n, int L, double(*F)(double,double)); 
double ImplicitWOWA(double x[], double p[], double w[], int n );
