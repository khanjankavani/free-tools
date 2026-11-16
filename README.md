# Free tools by Khanjan Kavani

The source code of the 20 free tools on [khanjankavani.com/tools](https://khanjankavani.com/tools/): GST, income tax, EMI, SIP, FD, RD and PPF calculators, an invoice generator, a QR code maker and more.

**Use them live at [khanjankavani.com/tools](https://khanjankavani.com/tools/).**

- Every tool is one HTML file with plain JavaScript. No framework, no build step.
- Everything runs in your browser. Your numbers, text and photos never leave your device.
- No ads and no analytics. The site loads nothing from any other domain.

### Money and tax (India)

| Tool | What it does | Code |
|---|---|---|
| [GST Calculator](https://khanjankavani.com/tools/gst-calculator/) | Add or Remove GST, CGST and SGST Split | [`tools/gst-calculator`](tools/gst-calculator/index.html) |
| [Income Tax Calculator FY 2026-27](https://khanjankavani.com/tools/income-tax-calculator/) | New vs Old Regime | [`tools/income-tax-calculator`](tools/income-tax-calculator/index.html) |
| [Free GST Invoice Generator](https://khanjankavani.com/tools/invoice-generator/) | Make and Print an Invoice | [`tools/invoice-generator`](tools/invoice-generator/index.html) |
| [EMI Calculator](https://khanjankavani.com/tools/emi-calculator/) | Home, Car and Personal Loan EMI in Rupees | [`tools/emi-calculator`](tools/emi-calculator/index.html) |
| [Loan Eligibility Calculator](https://khanjankavani.com/tools/loan-eligibility-calculator/) | How Much Will a Bank Lend You | [`tools/loan-eligibility-calculator`](tools/loan-eligibility-calculator/index.html) |
| [SIP Calculator](https://khanjankavani.com/tools/sip-calculator/) | Monthly Mutual Fund Investment Returns | [`tools/sip-calculator`](tools/sip-calculator/index.html) |
| [FD Calculator](https://khanjankavani.com/tools/fd-calculator/) | Fixed Deposit Maturity Amount and Interest | [`tools/fd-calculator`](tools/fd-calculator/index.html) |
| [RD Calculator](https://khanjankavani.com/tools/rd-calculator/) | Recurring Deposit Maturity Value | [`tools/rd-calculator`](tools/rd-calculator/index.html) |
| [PPF Calculator](https://khanjankavani.com/tools/ppf-calculator/) | Public Provident Fund Maturity in 15 Years | [`tools/ppf-calculator`](tools/ppf-calculator/index.html) |

### Everyday

| Tool | What it does | Code |
|---|---|---|
| [Percentage Calculator](https://khanjankavani.com/tools/percentage-calculator/) | Increase, Decrease and Difference | [`tools/percentage-calculator`](tools/percentage-calculator/index.html) |
| [Age Calculator](https://khanjankavani.com/tools/age-calculator/) | Exact Age in Years, Months and Days | [`tools/age-calculator`](tools/age-calculator/index.html) |
| [Date Calculator](https://khanjankavani.com/tools/date-calculator/) | Days Between Dates and Date Arithmetic | [`tools/date-calculator`](tools/date-calculator/index.html) |
| [Unit Converter](https://khanjankavani.com/tools/unit-converter/) | Length, Weight, Temperature and Area | [`tools/unit-converter`](tools/unit-converter/index.html) |
| [BMI Calculator](https://khanjankavani.com/tools/bmi-calculator/) | Body Mass Index with Healthy Range | [`tools/bmi-calculator`](tools/bmi-calculator/index.html) |

### Text and files

| Tool | What it does | Code |
|---|---|---|
| [Word Counter](https://khanjankavani.com/tools/word-counter/) | Words, Characters, Sentences and Reading Time | [`tools/word-counter`](tools/word-counter/index.html) |
| [Case Converter](https://khanjankavani.com/tools/case-converter/) | Sentence Case, Title Case, Upper and Lower | [`tools/case-converter`](tools/case-converter/index.html) |
| [Image Compressor](https://khanjankavani.com/tools/image-compressor/) | Shrink Photos Without Uploading Them | [`tools/image-compressor`](tools/image-compressor/index.html) |
| [QR Code Generator](https://khanjankavani.com/tools/qr-code-generator/) | Link, UPI, WiFi and Text | [`tools/qr-code-generator`](tools/qr-code-generator/index.html) |
| [Password Generator](https://khanjankavani.com/tools/password-generator/) | Strong Random Passwords, Made Offline | [`tools/password-generator`](tools/password-generator/index.html) |
| [Typing Speed Test](https://khanjankavani.com/tools/typing-speed-test/) | Words Per Minute and Accuracy | [`tools/typing-speed-test`](tools/typing-speed-test/index.html) |

## Run them on your computer

The pages use paths like `/assets/style.css`, so serve the repo folder instead of opening a file directly:

```
python -m http.server 8000
```

Then open http://localhost:8000/tools/

## Notes

- Tax and GST rules change. Check results against official sources before you rely on them.
- The live site self-hosts its fonts; they are not bundled here, so pages use system fonts when run locally.

## Licence

MIT, see [LICENSE](LICENSE). Third-party code: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Made by [Khanjan Kavani](https://khanjankavani.com) in Surat, India. I also build [Android apps](https://khanjankavani.com/apps/) and [custom business software](https://khanjankavani.com/work/).
