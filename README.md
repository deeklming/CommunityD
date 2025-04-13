# CommunityD
Community Service Project

## Service Name
CommuDD

## Working Period
2025.04.13 ~ ...ing

## Function
1. User CRUD
2. Post CRUD

## front-next
```bash
npx create-next-app@latest

npm i validator date-fns date-fns-tz smol-toml pino iron-session argon2 zustand ioredis nodemailer fflate "cropperjs@1.6.2" "@tabler/icons-react" "@noble/ciphers" "@noble/curves" "@noble/hashes" "@prisma/client"
npm i -D react-lorem-ipsum prisma "@types/validator" "@types/nodemailer" "daisyui@latest"

npx prisma init
npx prisma studio
npx prisma migrate dev --name init
npx prisma generate
npx prisma generate --sql
```

## back-fastapi
```bash
python -m venv bfvenv
bfvenv\Scripts\activate
pip freeze > requirements.txt
pip install -r requirements.txt
pip install "fastapi[standard]" "redis[hiredis]" argon2-cffi
```
