# Seating Plan Generator

A single-file classroom seating plan tool for teachers. No install and no internet needed — open `index.html` in any modern browser.

**Live page:** https://iverlee83.github.io/seating-plan/

## What it does

- Enter the number of students and the group size, or upload a class list
- **Class lists** from `.xlsx` or `.csv` (class number + name columns, English or Chinese headers), or pasted in by hand
- **Arrangements**: group pods, pairs (two desks joined), single exam rows, U-shape / horseshoe
- **Drag and drop**: drag a student onto a desk, drag desk to desk to swap, click a desk to unseat
- **Arrange mode**: move any desk anywhere, rotate in 45° steps, snap to grid, lasso-select several at once
- **Room fixtures**: teacher's desk, door, window, cupboard, free text labels
- **Teacher's view** mirroring, so the plan matches what you see standing at the front
- **Export** to PDF (A4 landscape), Word, or PNG
- The last plan is remembered in the browser and restored when the page is reopened

Each desk shows the student's name with the class number after it in brackets, e.g. `Chan Tai Man (12)`.

## Privacy

Everything runs in your own browser. No class data is sent anywhere — the saved plan lives only in that browser's local storage.
