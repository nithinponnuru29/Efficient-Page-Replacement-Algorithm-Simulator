# Efficient-Page-Replacement-Algorithm-Simulator
Efficient Page Replacement Algorithm Simulator

Team Members

Nithin Ponnuru

Tanishq Naga Vinayak

Sahik Sahuil

Project Description

Efficient Page Replacement Algorithm Simulator is a tool designed to analyze and compare various page replacement algorithms used in operating systems. This simulator helps understand how different algorithms handle memory management and optimize page faults.

Features

Simulates multiple page replacement algorithms: FIFO, LRU, LFU, MFU, and Optimal

Allows users to input page references manually or generate them randomly

Provides a detailed output of memory states after each page reference

Calculates and displays page faults, page hits, miss ratio, and hit ratio

Generates a comparative visualization of algorithm performance using Matplotlib

Technologies Used

Programming Language: Python

Libraries and Tools: Matplotlib, Collections (Deque & Counter), Random

Other Tools: GitHub for version control

Installation

Clone the repository:

git clone https://github.com/your-repo/efficient-page-replacement.git
cd efficient-page-replacement

Install dependencies:

pip install matplotlib

Run the simulator:

python page_replacement.py

Usage

Enter the length of the page reference string.

Choose to enter page references manually or generate them randomly.

Specify the number of frames.

Select the algorithms to simulate.

View the output with page hits, faults, and a comparison graph.

Example Output

Generated Page References: [1, 2, 3, 2, 1, 4, 5, 2, 1, 3, 4, 5]
Enter the number of frames: 3
Selected Algorithms: FIFO, LRU

FIFO Algorithm:
1 : 1
2 : 1 2
3 : 1 2 3
2 : 1 2 3 (hit)
...
Page Faults: 8, Page Hits: 4
Miss Ratio: 66.67%, Hit Ratio: 33.33%

Future Enhancements

Implement more advanced algorithms like NRU and Working Set

Add GUI for better user experience

Extend simulation to real-time process memory management
