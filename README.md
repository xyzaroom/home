
# Xyzaroom Login Firebase Integration

## Langkah Penggunaan

1. **Aktifkan Firebase Authentication:**
   - Buka Firebase Console > Authentication > Sign-in method
   - Aktifkan metode Email/Password

2. **Jalankan secara lokal (opsional):**
   ```
   cd public
   python3 -m http.server 8080
   ```
   Buka `http://localhost:8080`

3. **Atau gunakan Firebase Hosting:**
   - `firebase init hosting` (pilih folder `public`)
   - `firebase deploy`

4. **Login:**
   Gunakan email & password dari user yang telah kamu buat di Firebase Authentication.
