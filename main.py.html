from telegram import Update
from telegram.ext import ApplicationBuilder, CommandHandler, ContextTypes
import google.generativeai as genai

TOKEN = "TELEGRAM_BOT_TOKEN"
GEMINI_API = "GEMINI_API_KEY"

genai.configure(api_key=GEMINI_API)

async def gemini(update: Update, context: ContextTypes.DEFAULT_TYPE):
    prompt = " ".join(context.args)

    model = genai.GenerativeModel("gemini-1.5-flash")
    response = model.generate_content(prompt)

    await update.message.reply_text(response.text)

app = ApplicationBuilder().token(TOKEN).build()

app.add_handler(CommandHandler("gemini", gemini))

app.run_polling()
