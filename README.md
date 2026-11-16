# Advanced OTP Verification

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/advanced-otp-verification/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A responsive, dependency-free OTP verification demo reconstructed from the supplied 19-second screen recording.

## Run
- Open `index.html` directly in a modern browser, or
- Run `python3 -m http.server 8000` in this folder and visit http://localhost:8000

## Demo
- Initial OTP: `123456`
- Enter six digits, paste a six-digit code, use arrow/backspace navigation, and submit.
- Resend generates a new random demo OTP and logs it in the browser console.
- The resend button uses a 30-second cooldown.

## Important source note
The recording visibly shows the `.otp-input` and `.otp-input:focus` CSS rules and the visual interaction states. It does not expose a complete source file or backend/API implementation. This project preserves the readable CSS values and recreates the rest of the visible interface and client-side behavior as a runnable demo. It does not send SMS or perform real identity verification.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
