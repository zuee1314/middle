# middle
middle
int J(int n, int q) {
    int D = 1, end = (q-1)*n;
    while (D <= end) {
        D = (q*D+q-2)/(q-1);
    }
    return q*n+1-D;
}
