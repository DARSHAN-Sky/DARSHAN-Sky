<svg viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @media (prefers-color-scheme: dark) {
        .bg { fill: #0d1117; }
        .text-name { fill: #58a6ff; }
        .text-role { fill: #79c0ff; }
        .text-location { fill: #a371f7; }
        .accent-line { stroke: #58a6ff; }
      }
      @media (prefers-color-scheme: light) {
        .bg { fill: #ffffff; }
        .text-name { fill: #0969da; }
        .text-role { fill: #1158c7; }
        .text-location { fill: #6639ba; }
        .accent-line { stroke: #0969da; }
      }
      
      .bg { fill: #0d1117; }
      .text-name { fill: #58a6ff; font-size: 72px; font-weight: bold; font-family: 'Courier New', monospace; }
      .text-role { fill: #79c0ff; font-size: 48px; font-family: 'Courier New', monospace; }
      .text-location { fill: #a371f7; font-size: 36px; font-family: 'Courier New', monospace; }
      .accent-line { stroke: #58a6ff; stroke-width: 3; }
      
      @keyframes slideIn {
        from { opacity: 0; transform: translateX(-50px); }
        to { opacity: 1; transform: translateX(0); }
      }
      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 5px #58a6ff); }
        50% { filter: drop-shadow(0 0 15px #58a6ff); }
      }
      
      .name-text { animation: slideIn 1s ease-out, glow 2s infinite; }
      .role-text { animation: slideIn 1.2s ease-out, glow 2s infinite 0.3s; }
      .location-text { animation: slideIn 1.4s ease-out, glow 2s infinite 0.6s; }
    </style>
  </defs>
  
  <!-- Background -->
  <rect width="1200" height="400" class="bg"/>
  
  <!-- Accent line top -->
  <line x1="50" y1="60" x2="350" y2="60" class="accent-line"/>
  
  <!-- Name -->
  <text x="100" y="130" class="text-name name-text">DARSHAN</text>
  
  <!-- Role -->
  <text x="100" y="200" class="text-role role-text">AIML ENGINEER</text>
  
  <!-- Location with icon -->
  <circle cx="90" cy="260" r="6" fill="#a371f7"/>
  <text x="110" y="270" class="text-location location-text">📍 INDIA</text>
  
  <!-- Accent line bottom -->
  <line x1="50" y1="310" x2="350" y2="310" class="accent-line"/>
  
  <!-- Decorative dots -->
  <circle cx="1050" cy="80" r="4" fill="#58a6ff" opacity="0.5"/>
  <circle cx="1100" cy="120" r="6" fill="#79c0ff" opacity="0.4"/>
  <circle cx="1150" cy="160" r="5" fill="#a371f7" opacity="0.5"/>
  <circle cx="1120" cy="220" r="4" fill="#58a6ff" opacity="0.3"/>
</svg>
<svg viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      .bg { fill: #ffffff; }
      .text-name { fill: #0969da; font-size: 72px; font-weight: bold; font-family: 'Courier New', monospace; }
      .text-role { fill: #1158c7; font-size: 48px; font-family: 'Courier New', monospace; }
      .text-location { fill: #6639ba; font-size: 36px; font-family: 'Courier New', monospace; }
      .accent-line { stroke: #0969da; stroke-width: 3; }
      
      @keyframes slideIn {
        from { opacity: 0; transform: translateX(-50px); }
        to { opacity: 1; transform: translateX(0); }
      }
      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 5px #0969da); }
        50% { filter: drop-shadow(0 0 15px #0969da); }
      }
      
      .name-text { animation: slideIn 1s ease-out, glow 2s infinite; }
      .role-text { animation: slideIn 1.2s ease-out, glow 2s infinite 0.3s; }
      .location-text { animation: slideIn 1.4s ease-out, glow 2s infinite 0.6s; }
    </style>
  </defs>
  
  <!-- Background -->
  <rect width="1200" height="400" class="bg"/>
  
  <!-- Accent line top -->
  <line x1="50" y1="60" x2="350" y2="60" class="accent-line"/>
  
  <!-- Name -->
  <text x="100" y="130" class="text-name name-text">DARSHAN</text>
  
  <!-- Role -->
  <text x="100" y="200" class="text-role role-text">AIML ENGINEER</text>
  
  <!-- Location with icon -->
  <circle cx="90" cy="260" r="6" fill="#6639ba"/>
  <text x="110" y="270" class="text-location location-text">📍 INDIA</text>
  
  <!-- Accent line bottom -->
  <line x1="50" y1="310" x2="350" y2="310" class="accent-line"/>
  
  <!-- Decorative dots -->
  <circle cx="1050" cy="80" r="4" fill="#0969da" opacity="0.5"/>
  <circle cx="1100" cy="120" r="6" fill="#1158c7" opacity="0.4"/>
  <circle cx="1150" cy="160" r="5" fill="#6639ba" opacity="0.5"/>
  <circle cx="1120" cy="220" r="4" fill="#0969da" opacity="0.3"/>
</svg>
<svg viewBox="0 0 400 500" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @media (prefers-color-scheme: dark) {
        .card-bg { fill: #161b22; stroke: #58a6ff; }
        .card-text-name { fill: #58a6ff; }
        .card-text-role { fill: #79c0ff; }
        .card-text-location { fill: #a371f7; }
        .card-text-email { fill: #79c0ff; }
        .lanyard-line { stroke: #58a6ff; }
      }
      @media (prefers-color-scheme: light) {
        .card-bg { fill: #f6f8fa; stroke: #0969da; }
        .card-text-name { fill: #0969da; }
        .card-text-role { fill: #1158c7; }
        .card-text-location { fill: #6639ba; }
        .card-text-email { fill: #1158c7; }
        .lanyard-line { stroke: #0969da; }
      }
      
      .card-bg { fill: #161b22; stroke: #58a6ff; stroke-width: 2; }
      .card-text-name { fill: #58a6ff; font-size: 32px; font-weight: bold; font-family: 'Courier New', monospace; }
      .card-text-role { fill: #79c0ff; font-size: 20px; font-family: 'Courier New', monospace; }
      .card-text-location { fill: #a371f7; font-size: 16px; font-family: 'Courier New', monospace; }
      .card-text-email { fill: #79c0ff; font-size: 14px; font-family: 'Courier New', monospace; }
      .lanyard-line { stroke: #58a6ff; stroke-width: 4; }
      
      @keyframes swing {
        0%, 100% { transform: rotateZ(0deg); transform-origin: 200px 0; }
        50% { transform: rotateZ(3deg); transform-origin: 200px 0; }
      }
      @keyframes pulse {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.8; }
      }
      
      .card-group { animation: swing 3s ease-in-out infinite; }
      .glow-effect { animation: pulse 2s ease-in-out infinite; }
    </style>
  </defs>
  
  <!-- Lanyard string -->
  <line x1="200" y1="0" x2="200" y2="50" class="lanyard-line"/>
  
  <!-- Card group (swings) -->
  <g class="card-group glow-effect">
    <!-- ID Card -->
    <rect x="50" y="60" width="300" height="380" rx="15" class="card-bg"/>
    
    <!-- Card header line -->
    <line x1="60" y1="100" x2="340" y2="100" class="lanyard-line"/>
    
    <!-- Profile section -->
    <circle cx="200" cy="140" r="30" fill="#58a6ff" opacity="0.3"/>
    <text x="200" y="150" text-anchor="middle" font-size="40" text-decoration="none">👨‍💻</text>
    
    <!-- Name -->
    <text x="200" y="200" text-anchor="middle" class="card-text-name">DARSHAN</text>
    
    <!-- Role -->
    <text x="200" y="235" text-anchor="middle" class="card-text-role">AIML ENGINEER</text>
    
    <!-- Divider -->
    <line x1="70" y1="250" x2="330" y2="250" class="lanyard-line" opacity="0.5"/>
    
    <!-- Location -->
    <text x="70" y="290" class="card-text-location">📍 Location:</text>
    <text x="70" y="315" class="card-text-location" font-size="16">INDIA</text>
    
    <!-- Email -->
    <text x="70" y="355" class="card-text-email">📧 Email:</text>
    <text x="70" y="375" class="card-text-email" font-size="12">darshan07062008@gmail.com</text>
    
    <!-- Quote -->
    <text x="70" y="410" class="card-text-email" font-size="13" font-style="italic">"Always learning,</text>
    <text x="70" y="428" class="card-text-email" font-size="13" font-style="italic">always coding"</text>
  </g>
</svg><svg viewBox="0 0 400 500" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @media (prefers-color-scheme: dark) {
        .card-bg { fill: #161b22; stroke: #58a6ff; }
        .card-text-name { fill: #58a6ff; }
        .card-text-role { fill: #79c0ff; }
        .card-text-location { fill: #a371f7; }
        .card-text-email { fill: #79c0ff; }
        .lanyard-line { stroke: #58a6ff; }
      }
      @media (prefers-color-scheme: light) {
        .card-bg { fill: #f6f8fa; stroke: #0969da; }
        .card-text-name { fill: #0969da; }
        .card-text-role { fill: #1158c7; }
        .card-text-location { fill: #6639ba; }
        .card-text-email { fill: #1158c7; }
        .lanyard-line { stroke: #0969da; }
      }
      
      .card-bg { fill: #161b22; stroke: #58a6ff; stroke-width: 2; }
      .card-text-name { fill: #58a6ff; font-size: 32px; font-weight: bold; font-family: 'Courier New', monospace; }
      .card-text-role { fill: #79c0ff; font-size: 20px; font-family: 'Courier New', monospace; }
      .card-text-location { fill: #a371f7; font-size: 16px; font-family: 'Courier New', monospace; }
      .card-text-email { fill: #79c0ff; font-size: 14px; font-family: 'Courier New', monospace; }
      .lanyard-line { stroke: #58a6ff; stroke-width: 4; }
      
      @keyframes swing {
        0%, 100% { transform: rotateZ(0deg); transform-origin: 200px 0; }
        50% { transform: rotateZ(3deg); transform-origin: 200px 0; }
      }
      @keyframes pulse {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.8; }
      }
      
      .card-group { animation: swing 3s ease-in-out infinite; }
      .glow-effect { animation: pulse 2s ease-in-out infinite; }
    </style>
  </defs>
  
  <!-- Lanyard string -->
  <line x1="200" y1="0" x2="200" y2="50" class="lanyard-line"/>
  
  <!-- Card group (swings) -->
  <g class="card-group glow-effect">
    <!-- ID Card -->
    <rect x="50" y="60" width="300" height="380" rx="15" class="card-bg"/>
    
    <!-- Card header line -->
    <line x1="60" y1="100" x2="340" y2="100" class="lanyard-line"/>
    
    <!-- Profile section -->
    <circle cx="200" cy="140" r="30" fill="#58a6ff" opacity="0.3"/>
    <text x="200" y="150" text-anchor="middle" font-size="40" text-decoration="none">👨‍💻</text>
    
    <!-- Name -->
    <text x="200" y="200" text-anchor="middle" class="card-text-name">DARSHAN</text>
    
    <!-- Role -->
    <text x="200" y="235" text-anchor="middle" class="card-text-role">AIML ENGINEER</text>
    
    <!-- Divider -->
    <line x1="70" y1="250" x2="330" y2="250" class="lanyard-line" opacity="0.5"/>
    
    <!-- Location -->
    <text x="70" y="290" class="card-text-location">📍 Location:</text>
    <text x="70" y="315" class="card-text-location" font-size="16">INDIA</text>
    
    <!-- Email -->
    <text x="70" y="355" class="card-text-email">📧 Email:</text>
    <text x="70" y="375" class="card-text-email" font-size="12">darshan07062008@gmail.com</text>
    
    <!-- Quote -->
    <text x="70" y="410" class="card-text-email" font-size="13" font-style="italic">"Always learning,</text>
    <text x="70" y="428" class="card-text-email" font-size="13" font-style="italic">always coding"</text>
  </g>
</svg>
<div align="center">

<!-- ✨ Animated Banner — auto-switches dark/light ✨ -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./banner.svg?v=1">
  <source media="(prefers-color-scheme: light)" srcset="./banner-light.svg?v=1">
  <img src="./banner.svg?v=1" alt="DARSHAN — AIML Engineer" width="100%"/>
</picture>

</div>

<br/>

<table align="center" border="0">
<tr>
<td width="38%" align="center" valign="middle">

<!-- 🪪 Swinging Lanyard ID Card -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./lanyard.svg?v=1">
  <source media="(prefers-color-scheme: light)" srcset="./lanyard.svg?v=1">
  <img src="./lanyard.svg?v=1" alt="DARSHAN ID Badge" width="330"/>
</picture>

</td>
<td width="62%" valign="middle">

### ☕ Quick About Me

```python
class DARSHAN:
    def __init__(self):
        self.role = "AIML Engineer"
        self.location = "India"
        self.email = "darshan07062008@gmail.com"
        self.quote = "Always learning, always coding"
        self.passion = "AI/ML Development"
