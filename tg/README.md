# Legal Documents for ScheduleMe Telegram Bot

This directory contains the Privacy Policy and Terms of Service documents for ScheduleMe Telegram Bot in three languages.

## Files

### Privacy Policy
- `privacy-policy-uk.md` - Ukrainian version (Українська)
- `privacy-policy-en.md` - English version
- `privacy-policy-ru.md` - Russian version (Русский)
- `privacy-policy-uk.html` - Ukrainian HTML page
- `privacy-policy-en.html` - English HTML page
- `privacy-policy-ru.html` - Russian HTML page

### Terms of Service
- `terms-of-service-uk.md` - Ukrainian version (Українська)
- `terms-of-service-en.md` - English version
- `terms-of-service-ru.md` - Russian version (Русский)
- `terms-of-service-uk.html` - Ukrainian HTML page
- `terms-of-service-en.html` - English HTML page
- `terms-of-service-ru.html` - Russian HTML page

### Main Page
- `index.html` - Legal documents hub with language selection

## GitHub Pages Setup

These files are designed to be deployed on GitHub Pages. Once deployed, the legal documents will be accessible at:

```
https://uabeseda.github.io/schedule-me/legal/
```

### Deployment Steps

1. **Enable GitHub Pages** for the repository:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: Select your main branch
   - Folder: `/` (root)
   - Click Save

2. **Wait for deployment** (usually takes 1-2 minutes)

3. **Access the legal documents**:
   - **Main page**: `https://uabeseda.github.io/schedule-me/legal/index.html`

   **Privacy Policy:**
   - Ukrainian: `https://uabeseda.github.io/schedule-me/legal/privacy-policy-uk.html`
   - English: `https://uabeseda.github.io/schedule-me/legal/privacy-policy-en.html`
   - Russian: `https://uabeseda.github.io/schedule-me/legal/privacy-policy-ru.html`

   **Terms of Service:**
   - Ukrainian: `https://uabeseda.github.io/schedule-me/legal/terms-of-service-uk.html`
   - English: `https://uabeseda.github.io/schedule-me/legal/terms-of-service-en.html`
   - Russian: `https://uabeseda.github.io/schedule-me/legal/terms-of-service-ru.html`

## BotFather Configuration

Once the privacy policy is deployed on GitHub Pages, configure it in BotFather:

### Step 1: Open BotFather

1. Open Telegram and search for `@BotFather`
2. Start a chat with BotFather

### Step 2: Set Privacy Policy

1. Send the command: `/setprivacy`
2. Select your bot from the list (e.g., `@your_bot_name`)
3. Send the Privacy Policy URL:
   ```
   https://uabeseda.github.io/schedule-me/legal/index.html
   ```
4. BotFather will confirm: "Success! Privacy policy URL has been updated."

### Step 3: Verify

Users can now:
- See the Privacy Policy link in your bot's info page
- Access it by typing `/privacy` in the bot chat
- View the link in the bot's description

### Optional: Update Bot Description

You can also mention the privacy policy in your bot description:

1. Send: `/setdescription` to BotFather
2. Select your bot
3. Add text like:
   ```
   ScheduleMe - Booking platform for service specialists.

   📅 Book appointments
   🔍 Find specialists nearby
   🔒 Privacy Policy: /privacy
   ```

## Bot Commands

The bot now supports legal document commands:

### `/privacy` Command

Displays Privacy Policy links:

```
🔒 Политика конфиденциальности ScheduleMe Bot

Мы серьезно относимся к защите ваших персональных данных.

Ознакомьтесь с нашей Политикой конфиденциальности:

🇺🇦 Українська версія
🇬🇧 English version
🇷🇺 Русская версия

Последнее обновление: 16 января 2026

Вопросы? Напишите → @book_me_io
```

### `/terms` Command

Displays Terms of Service links:

```
📜 Условия использования ScheduleMe Bot

Пожалуйста, ознакомьтесь с правилами использования нашего сервиса.

Условия использования доступны на трёх языках:

🇺🇦 Українська версія
🇬🇧 English version
🇷🇺 Русская версия

Последнее обновление: 16 января 2026

Вопросы? Напишите → @book_me_io
```

## Updating Legal Documents

To update the Privacy Policy or Terms of Service:

1. Edit the corresponding `.md` files in this directory
2. Update the "Last Updated" date in all three language versions
3. Commit and push changes to the repository
4. GitHub Pages will automatically rebuild (1-2 minutes)
5. The new version will be live

## Compliance

These legal documents are designed to comply with:

- ✅ **GDPR** (General Data Protection Regulation) - EU
- ✅ **Ukraine Law on Personal Data Protection**
- ✅ **Telegram Bot Platform Requirements**
- ✅ **CCPA** (California Consumer Privacy Act) - USA
- ✅ **Consumer protection laws** - Fair service usage terms

## Contact

For questions about Privacy Policy or Terms of Service:

- **Telegram:** [@book_me_io](https://t.me/book_me_io)
- **GitHub Issues:** [github.com/uabeseda/schedule-me/issues](https://github.com/uabeseda/schedule-me/issues)
