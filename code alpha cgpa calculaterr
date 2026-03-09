#include <iostream>
#include <vector>
using namespace std;

int main() {
    int n;
    float grade, credit;
    float totalCredits = 0;
    float totalGradePoints = 0;

    cout << "===== CGPA Calculator =====" << endl;
    cout << "Enter number of courses: ";
    cin >> n;

    vector<float> grades(n);
    vector<float> credits(n);

    for(int i = 0; i < n; i++) {
        cout << "\nCourse " << i + 1 << endl;
        cout << "Enter Grade (e.g., 8.5): ";
        cin >> grades[i];
        cout << "Enter Credit Hours: ";
        cin >> credits[i];

        totalCredits += credits[i];
        totalGradePoints += grades[i] * credits[i];
    }

    float cgpa = totalGradePoints / totalCredits;

    cout << "\n===== Result =====" << endl;
    cout << "Total Credits: " << totalCredits << endl;
    cout << "Total Grade Points: " << totalGradePoints << endl;
    cout << "Final CGPA: " << cgpa << endl;

    return 0;
}
