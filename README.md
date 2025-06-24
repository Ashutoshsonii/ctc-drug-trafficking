# ctc-drug-trafficking
Capture The Criminal drug trafficking mission
git clone https://github.com/your-username/ctc-drug-trafficking-scenario.git
cd ctc-drug-trafficking-scenario
ctc-drug-trafficking-scenario/
│
├── README.md
├── SCENARIO.md        
├── CHARACTERS/
│   ├── the_broker.md
│   ├── raven.md
│   └── torch.md
│
├── LOCATIONS/
│   ├── greybridge_docks.md
│   ├── warehouse.md
│   └── final_bust_site.md
│
├── CLUES/
│   ├── shipping_docs.pdf
│   ├── chat_logs.txt
│   └── surveillance_images/
│       ├── camera1.jpg
│       └── map_route.png
│
└── PUZZLES/
    ├── decrypt_passphrase.py
    ├── password_hint.txt
    └── crypto_wallet_hint.txt

mkdir CHARACTERS LOCATIONS CLUES PUZZLES
touch SCENARIO.md CHARACTERS/the_broker.md ...
git add .
git commit -m "Add initial CTC scenario files and structure"
git push origin main
