# How Many Mondays Until Next Tet?

A simple, interactive web tool that calculates how many Mondays remain until the next Vietnamese Lunar New Year (Tết Nguyên Đán). It determines the exact Gregorian date of the next Tet based on the Vietnamese lunar calendar rules and then counts the number of Mondays between today and that date.

## 🚀 Live Demo

Check out the live demo: [https://www.sieu.io.vn/github/how-many-Mondays-until-next-Tet](https://www.sieu.io.vn/github/how-many-Mondays-until-next-Tet)

## ✨ Features

- **Automatic Tet Date Calculation** – Determines the exact Gregorian date of the next Vietnamese Lunar New Year based on the official Vietnamese lunar calendar rules
- **Monday Countdown** – Counts the number of Mondays remaining between today and the next Tet
- **Real-Time Results** – Displays the result instantly upon page load or calculation
- **Clean Interface** – Simple, user-friendly design with a clear layout
- **Responsive Design** – Works seamlessly on desktop, tablet, and mobile devices

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## 📁 Project Structure

```
how-many-Mondays-until-next-Tet/
├── index.html                    # Main HTML file
├── style.css                     # Stylesheet
├── script.js                     # JavaScript logic for lunar calendar calculation and Monday counting
└── README.md                     # Project documentation
```

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/lemasieu/how-many-Mondays-until-next-Tet.git
   ```
2. **Navigate to the project folder**   
   ```bash
   cd how-many-Mondays-until-next-Tet
   ```
3. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local development server (e.g., Live Server in VS Code)

## 📝 How It Works

1. **Open the application** – The tool automatically loads and begins the calculation
2. **View the result** – The page displays:
   - The exact Gregorian date of the next Tet
   - The number of Mondays remaining until that date
3. **Understand the calculation** – The tool uses the Vietnamese lunar calendar rules to determine the date of the next Lunar New Year, then counts all Mondays between today and that date

**Lunar Calendar Rules Reference:**

The calculation of the Vietnamese lunar calendar is based on the following principles:

- The first day of a lunar month is the day containing the **Sóc** (New Moon) point
- A normal year has 12 lunar months; a leap year has 13 lunar months
- **Đông chí** (Winter Solstice) always falls in the 11th lunar month
- In a leap year, if a month has no **Trung khí** (Major Solar Term), that month is the leap month. If multiple months lack a Trung khí, only the first month after Đông chí is the leap month
- Calculations are based on the **105° East longitude** meridian

**Sóc** is the moment of conjunction, when the Earth, Moon, and Sun are aligned, with the Moon between the Earth and the Sun. The cycle of the Sóc point is approximately 29.5 days. The day containing the Sóc point is called the **Sóc day**, and it marks the beginning of a lunar month-39.

**Trung khí** are the points that divide the ecliptic into 12 equal parts. The four most special Trung khí are the midpoints of the four seasons: **Xuân phân** (Vernal Equinox, ~March 20), **Hạ chí** (Summer Solstice, ~June 22), **Thu phân** (Autumnal Equinox, ~September 23), and **Đông chí** (Winter Solstice, ~December 22)-39.

Because it is based on both the Sun and the Moon, the Vietnamese calendar is not purely lunar but a **lunisolar calendar**.

> Reference: The lunar calendar calculation rules used in this project are based on the algorithm described by Hồ Ngọc Đức at [https://www.xemamlich.uhm.vn/calrules.html](https://www.xemamlich.uhm.vn/calrules.html).

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License
This project is open-source and available under the MIT License.
