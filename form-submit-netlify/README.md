# 📬 Simple Contact Form with Netlify

This is a minimal HTML contact form that uses [Netlify Forms](https://docs.netlify.com/forms/setup/) to handle form submissions — no backend or JavaScript required.

## 🛠 Tech Stack

- HTML5
- Bootstrap 5
- Netlify (for deployment + form handling)

## 🚀 Live Demo

👉 [Live site on Netlify](https://form-submit-netlify.netlify.app/)

## 💡 How It Works

1. The form uses `method="POST"` and `data-netlify="true"` to activate Netlify’s form capture.
2. A hidden field `<input type="hidden" name="form-name" value="contact" />` is required.
3. Submissions can be viewed in the **Forms** tab on the Netlify dashboard.
4. You can set up email notifications in the form settings.

## 📂 How to Use

1. Clone or fork this repo
2. Modify `index.html` if needed
3. Deploy to [Netlify](https://www.netlify.com/)
4. Done! 🎉

## 🙌 Credits

Created by [Yuliia](https://github.com/ykuts)
