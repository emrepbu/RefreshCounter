# Refresh Counter

This project is a simple web page that displays how many times the page has been refreshed. The counter value is stored in the browser using `localStorage` and increases by one on each reload. The displayed value is animated using GSAP for a smooth transition. A reset button is also included to manually reset the counter to zero.

## Features

- Counter increases on every page refresh
- Smooth animation with GSAP
- Persistent data using localStorage
- Reset button to manually reset the counter
- Clean dark UI with Poppins font

## Technologies Used

- HTML5
- CSS3
- JavaScript
- GSAP (GreenSock Animation Platform)
- Google Fonts (Poppins)

## How to Use

1. Clone this repository:
```bash
git clone https://github.com/emrepbu/RefreshCounter.git
```

2. Navigate into the project folder and open `index.html` in a browser.

## Notes

- The counter is specific to the browser and device (via localStorage).
- It increments by 1 on every refresh.
- You can reset the counter at any time by clicking the "Reset Counter" button.
