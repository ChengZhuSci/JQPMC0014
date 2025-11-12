DOI registered for Database-JQPMC0014 via Crossref: https://doi.org/10.58473/ChengZhuSci0001

The Database/Dataset DOI registered via ChengZhu Science can be retrieval from international databases, including Web of Science, Scilit database, PlumX, etc.

Reference: Liu Huan (2025). Fundamental mechanics: from classical mechanics to quantum mechanics and its application on quantum chemistry. Journal of Quantum Physics and Materials Chemistry (ISSN2958-4027). 2025 (09). https://doi.org/10.58473/JQPMC0014

The documents (uploaded in releases) of this database include Journal Article, Datasets, Software, Figures' Collection, Metadata registered for this Database (Crossref). 

All rights reserved.

<img width="1667" height="1667" alt="ChengZhu Science_画板 1" src="https://github.com/user-attachments/assets/6461bd72-0afe-482f-a84d-3da7c107b445" />

// @All rights reserved by Liu Huan. Source from: https://doi.org/10.58473/JEHS0012 

#include <iostream>
#include <cmath>
#include <vector>
using namespace std;

int main() {
    // Definition of Variables;
    double NPP, APAR, LUE, WLF, FPARA, LU, RPAR;
    vector<double> DR(90), FPARA_daily(90), VDR(90);
    double TDR, WB, Precipitation, E, Ev, Kv, LSP;
    double a, s, r;
    int V, P, n;

    cout << "=== Calculator of NPP for multiple plant species ===" << endl;
    
    // To input the species amount;
    cout << "Please input the species amount n (integer): ";
    cin >> n;
