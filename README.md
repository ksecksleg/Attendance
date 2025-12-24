# 🎄 Christmas Celebration Attendance System
## MAAGAP Guardians International with Philippine Eagles Kuwait

### Features / Mga Features:
- ✅ Real-time attendance registration
- 👑 Admin dashboard with full control
- 📊 Export to CSV
- 🔍 Search functionality
- 📱 Mobile-responsive design
- ❄️ Festive Christmas theme
- 🔐 Secure admin access

### Technologies Used:
- HTML5
- CSS3 with animations
- JavaScript (ES6+)
- Firebase Realtime Database
- Vercel Hosting

---

## 🚀 DEPLOYMENT INSTRUCTIONS / PAAGI SA PAG-DEPLOY

### Step 1: Setup Firebase
1. Go to https://firebase.google.com/
2. Create a new project named "christmas-celebration-2025"
3. Enable **Realtime Database**
4. Set database rules to:
```json
{
  "rules": {
    "attendance": {
      ".read": true,
      ".write": true
    }
  }
}
```
5. Copy your Firebase config and update in `index.html` (lines 383-390)

### Step 2: Deploy to Vercel
```bash
# Install Vercel CLI
npm install -g vercel

# Login to Vercel
vercel login

# Deploy
vercel --prod
```

### Step 3: Change Admin Password
- Open `index.html`
- Find line 397: `const ADMIN_PASSWORD = 'admin123';`
- Change to your secure password
- **IMPORTANTE:** Lig-a ang password, Kuya Heber!

---

## 📝 PAGGAMIT / HOW TO USE

### Para sa mga Attendees:
1. Ablihi ang website
2. I-fill up ang:
   - Full Name
   - Mobile Number
3. Click "Register Attendance"
4. Success! ✅

### Para sa Admin:
1. Click "Admin Access"
2. Enter password (default: admin123)
3. Makita nimo:
   - Total attendees
   - Full list with delete option
   - Search function
   - Export to CSV

### Admin Functions:
- **Search**: Type name or mobile number
- **Delete**: Click delete button per attendee
- **Export**: Download all data as CSV
- **Logout**: Secure logout

---

## 🎨 CUSTOMIZATION

### Colors:
- Red (#8B0000) - MAAGAP
- Green (#006400) - Philippine Eagles
- Gold (#FFD700) - Christmas accent

### Background:
Ang background naa sa Christmas theme with snowflakes animation!

---

## 📊 DATABASE STRUCTURE

```
attendance/
├── {uniqueId1}/
│   ├── name: "Juan Dela Cruz"
│   ├── mobile: "+965 1234 5678"
│   ├── timestamp: "2025-12-26T10:30:00.000Z"
│   └── date: "December 26, 2025, 10:30 AM"
├── {uniqueId2}/
│   └── ...
```

---

## 🔒 SECURITY NOTES

1. **Admin Password**: Change immediately!
2. **Firebase Rules**: Consider adding authentication
3. **Mobile Numbers**: Validate format if needed
4. **Data Privacy**: Inform attendees their data is stored

---

## 📱 MOBILE RESPONSIVE

- ✅ Smartphones
- ✅ Tablets
- ✅ Desktop
- ✅ All screen sizes

---

## ⭐ DEVELOPED BY

**Godmisoft**
- Developer: Heber Mayormita (Kuya Heber)
- Contact: [Your contact info]
- Website: [Your website]

---

## 🎄 MERRY CHRISTMAS! 🎆

*Unity and Hope - December 26, 2025*
*Old Souq, Salmiya, Kuwait*

---

## TROUBLESHOOTING

### Firebase not connecting:
- Check Firebase config
- Verify database rules
- Check internet connection

### Admin can't login:
- Verify password
- Check browser console for errors

### Export not working:
- Check if there's data
- Try different browser
- Check popup blockers

---

## FUTURE ENHANCEMENTS

- 📧 Email notifications
- 📸 Photo upload
- 🎫 QR code tickets
- 📱 SMS confirmation
- 🌐 Multi-language support

---

**Para sa support, contact Godmisoft!**

🎄 **Merry Christmas & Happy New Year!** 🎆
