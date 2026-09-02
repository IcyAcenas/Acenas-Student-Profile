<img width="1055" height="956" alt="image" src="https://github.com/user-attachments/assets/8969512a-0afa-43c3-9a36-b8b32e88c382" /># Acenas-Student-Profile
Activity 2 ITCC 41
1: I built my HTML
<img width="1920" height="1043" alt="image" src="https://github.com/user-attachments/assets/04c62058-4ea9-4481-99ab-218c3bf656d9" />
2: I built the CSS/Style for my HTML
<img width="1920" height="1036" alt="image" src="https://github.com/user-attachments/assets/35c45e5b-fd95-4082-b3b7-741977112c39" />
3: I ran it in Android Studio
<img width="1915" height="978" alt="image" src="https://github.com/user-attachments/assets/5047aa1f-3f3d-4478-95a6-fb40b9dbfa78" />

My Profile
<img width="249" height="523" alt="image" src="https://github.com/user-attachments/assets/2299c602-fcc2-4795-a66f-95377d851582" />
<img width="274" height="519" alt="image" src="https://github.com/user-attachments/assets/87f94eeb-b03d-46ad-9983-8f12cf289e05" />
<img width="296" height="523" alt="image" src="https://github.com/user-attachments/assets/3fcc7f31-d215-463e-9cd1-7993e5957e06" />

FOR ACTIVITY 3

I just changed my HTML code and my CSS code a little bit

New HTML code
<img width="1055" height="956" alt="image" src="https://github.com/user-attachments/assets/e4020043-34dd-4ed5-ad7a-9eaf21fefea3" />
<img width="1056" height="935" alt="image" src="https://github.com/user-attachments/assets/a41052d0-da47-4ee6-bdea-e3be0b5d0f09" />
<img width="1069" height="949" alt="image" src="https://github.com/user-attachments/assets/0b058f72-9762-442a-b80d-06268a2e0dfe" />

New CSS code
html {
  scroll-behavior: smooth;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #1a1744;
  color: #ffffff;
  line-height: 1.6;
  padding: 15px;
}

header {
  text-align: center;
  padding: 30px 15px;
  border-bottom: 2px solid #332d75;
  max-width: 1000px;
  margin: 0 auto;
}

.header-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 10px;
}

.profile-pic {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  border: 3px solid #6c5ce7;
  object-fit: cover;
  transition: transform 0.3s ease;
}

.profile-pic:hover {
  transform: scale(1.08);
}

.subtitle {
  color: #a5a2e8;
  font-style: italic;
  font-size: 1.05rem;
}

nav {
  margin-top: 20px;
  display: flex;
  justify-content: center;
  gap: 12px;
}

nav a {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  color: #ffffff;
  text-decoration: none;
  padding: 10px 24px;
  min-height: 44px;
  min-width: 90px;
  background-color: #332d75;
  border-radius: 6px;
  font-weight: bold;
  transition: background-color 0.3s ease, transform 0.2s ease, outline 0.2s ease;
}

nav a:hover, nav a:focus {
  background-color: #6c5ce7;
  transform: translateY(-3px);
  outline: 2px solid #ffffff;
}

main {
  max-width: 1000px;
  margin: 0 auto;
  padding: 25px 0;
}

section {
  background-color: #211c52;
  padding: 20px;
  border-radius: 10px;
  margin-bottom: 30px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
}

h2 {
  color: #ffffff;
  border-bottom: 2px solid #534bae;
  padding-bottom: 8px;
  margin-bottom: 18px;
  font-size: 1.5rem;
}

.about-text {
  margin-bottom: 15px;
  color: #e0e0e0;
  font-size: 1rem;
}

.about-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 12px;
  margin-top: 20px;
}

.about-card {
  background: #25215a;
  padding: 15px;
  border-left: 4px solid #6c5ce7;
  border-radius: 6px;
}

.about-card h3 {
  color: #a5a2e8;
  font-size: 1.05rem;
  margin-bottom: 6px;
}

.about-card p {
  font-size: 0.95rem;
  color: #e0e0e0;
  margin-bottom: 0;
}

.skills-container {
  display: grid;
  grid-template-columns: 1fr;
  gap: 15px;
}

.skill-card {
  background: #25215a;
  padding: 18px 20px;
  border-radius: 8px;
  border-left: 4px solid #332d75;
  transition: all 0.3s ease;
}

.skill-card:hover {
  border-left-color: #6c5ce7;
  background: #2e296d;
  transform: translateX(6px);
}

.skill-name {
  font-weight: bold;
  color: #ffffff;
  font-size: 1.05rem;
}

.skill-desc {
  font-size: 0.92rem;
  color: #c4c2f5;
  margin-top: 6px;
}

footer {
  text-align: center;
  padding: 20px;
  border-top: 2px solid #332d75;
  color: #a5a2e8;
  font-size: 0.9em;
  max-width: 1000px;
  margin: 0 auto;
}

@media (min-width: 600px) {
  body {
    padding: 30px;
  }

  .header-container {
    flex-direction: row;
    justify-content: center;
    text-align: left;
    gap: 20px;
  }

  section {
    padding: 25px;
  }

  .about-grid {
    grid-template-columns: repeat(3, 1fr);
  }

  .skills-container {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (min-width: 900px) {
  section {
    padding: 30px;
  }

  .skills-container {
    grid-template-columns: repeat(3, 1fr);
  }
}

Screenshots:

Phone:

<img width="1221" height="1044" alt="image" src="https://github.com/user-attachments/assets/b7f96b2d-d5f5-4078-90bd-222c1bd30940" />
<img width="1214" height="973" alt="image" src="https://github.com/user-attachments/assets/4163667a-95ee-4ae7-a482-b1a69bd2fc0a" />
<img width="1192" height="985" alt="image" src="https://github.com/user-attachments/assets/06980b0c-455f-4e83-a116-b8b66829a0ec" />
<img width="1221" height="968" alt="image" src="https://github.com/user-attachments/assets/67706661-59fb-468e-a093-1a26cf367927" />



Tablet:

<img width="1210" height="947" alt="image" src="https://github.com/user-attachments/assets/436c18a8-4047-427d-8d80-3a4a9a0b2e4f" />
<img width="1203" height="953" alt="image" src="https://github.com/user-attachments/assets/a065a6c2-f05b-42e0-b08f-b20ade22f2fd" />
<img width="1200" height="968" alt="image" src="https://github.com/user-attachments/assets/c0cc7148-58c1-4bfe-90bc-020998c51229" />

Desktop:
<img width="1227" height="995" alt="image" src="https://github.com/user-attachments/assets/c7105c86-c513-4256-a7e3-d28c47d78eb2" />
<img width="1213" height="983" alt="image" src="https://github.com/user-attachments/assets/38152446-dc90-45aa-b363-fc6c19877651" />
![Uploading image.png…]()


