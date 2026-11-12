# Example PayPal

A minimal static website that displays "Example Website".

## Project structure

```
.
├── index.html                 # The site (displays "Example Website")
├── README.md                  # This file
└── .github/workflows/ci.yml   # Continuous integration
```

## Setup

No dependencies or build step are required.

1. Clone the repository:

   ```bash
   git clone https://github.com/manasa1864/example_paypal.git
   cd example_paypal
   ```

2. Open `index.html` directly in your browser, **or** serve it locally:

   ```bash
   python3 -m http.server 8000
   ```

   Then visit <http://localhost:8000>.

## Continuous integration

A GitHub Actions workflow (`.github/workflows/ci.yml`) runs on every push and
pull request. It checks that `index.html` and `README.md` exist and that
`index.html` displays "Example Website".
