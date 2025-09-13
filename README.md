# Room-Seat-Booking
# Room/Seat Booking System – ServiceNow

## 📌 Objective
A ServiceNow-based **Room/Seat Booking System** that streamlines scheduling, prevents double-booking, and automates booking confirmations.

---

## 🚀 Features
- Submit booking requests (date, time, purpose, room).
- Prevent overlapping/double bookings.
- Auto-assign booking to logged-in user.
- Email confirmation on successful booking.
- Track booking status (Confirmed / Cancelled).
- Exportable via Update Set (XML).

---

## 🛠️ ServiceNow Concepts Used
- Custom Tables (`u_booking`, `u_room`)
- Service Catalog & Record Producer
- Producer Script (variable → field mapping)
- Business Rules (validation & automation)
- Notifications (email alerts)
- Update Sets (export/import)
  
---

## ✅ Testing
- **Positive Cases**: Successful booking, email confirmation.  
- **Negative Cases**: Overlapping bookings blocked, invalid dates rejected.  
- **Edge Cases**: Start > End time blocked, cancelled bookings handled.  

---

## 📌 Future Enhancements
- Approval workflow for restricted rooms.  
- Calendar view for bookings.  
- Support for seat-level booking.  
