# Install
> [!important]
> Need [nodejs](https://nodejs.org/en/download) and pnpm

Linux/MacOS:
```bash
git clone https://github.com/FuSoraS/birthday-26.git --depth=1 &&
cd birthday-26 &&
cp .env.example .env &&
pnpm install &&
pnpm run dev
```

Windows:
```bash
git clone https://github.com/FuSoraS/birthday-26.git --depth=1 &&
cd birthday-26 &&
copy .env.example .env &&
pnpm install &&
pnpm run dev
```

# ENV Variables Configuration
This project uses several environment variables to configure its behavior. The .env.example file has the variables needed for customization.