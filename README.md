# PLP Select — AI-Powered Recruitment Tool

**Author:** Sam Magqamfana  
**Role:** PLP Student  
**Email:** sammagqamfana4127@gmail.com  
**Phone:** 084 622 9609  

---

## Project Overview

PLP Select is an **AI-powered recruitment platform** designed to tackle Nigeria’s **youth unemployment crisis**.  
The system automates applicant ranking, reduces delays caused by manual processes, and ensures that skilled candidates are efficiently identified and recommended for programs and opportunities.  

---

## Problem Statement

- Nigeria’s youth unemployment exceeds **40%**  
- Millions of qualified candidates are **overlooked**  
- Manual recruitment processes **delay opportunity**  
- HR teams face **bottlenecks** in reviewing applicants  

---

## Solution

PLP Select solves these issues by:  
- Ranking applicants automatically using AI  
- Considering **skills, experience, education, and test scores**  
- Highlighting **top candidates** quickly  
- Providing **voice command search** and interactive charts  
- Being **ready for LMS integration**  

---

## Features

- Upload & rank CSV/JSON applicants  
- Merit-based scoring: Skills + Experience + Education + Test Score  
- Voice command to search/filter applicants  
- Interactive chart visualization of scores  
- Fully mobile-responsive interface  
- JSON API for backend integration  

---

## Scoring Logic

| Component     | Weight/Calculation                  |
|---------------|-----------------------------------|
| Skills        | 5 points per skill                 |
| Experience    | 4 points per year                  |
| Education     | Diploma → 5, Bachelor → 15, Master → 20, PhD → 25 |
| Test Score    | 0.6 × test score                   |
| Total Score   | Maximum 100                        |

---

## Setup Instructions

### Frontend Only
1. Open `index.html` in a modern web browser  
2. Ensure `style.css` and `script.js` are in the same folder  
3. Use the interface to upload, rank, search, and visualize applicants  

### Backend (Optional)
1. Navigate to the backend folder:  
```bash
cd backend
