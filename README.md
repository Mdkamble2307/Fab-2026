<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Birthday My Love ❤️</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.card {
  background: white;
  padding: 30px;
  border-radius: 20px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  max-width: 420px;
  text-align: center;
}

h1 { color: #ff4d6d; }

button {
  margin-top: 15px;
  padding: 12px 22px;
  font-size: 16px;
  border: none;
  border-radius: 30px;
  cursor: pointer;
  background: #ff4d6d;
  color: white;
}

button:hover { background: #e63956; }

/* Modal */
.modal {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.6);
  align-items: center;
  justify-content: center;
}

.modal-box {
  background: #fff;
  width: 90%;
  max-width: 500px;
  max-height: 80vh;
  padding: 20px;
  border-radius: 15px;
  overflow-y: auto;
  white-space: pre-wrap;
}

.close {
  text-align: right;
  font-size: 18px;
  cursor: pointer;
  color: #ff4d6d;
}
</style>
</head>

<body>

<div class="card">
  <h1>🎉 Happy Birthday My Beloved Kalpana 🎉</h1>
  <p>
    You fill my life with happiness and love 💕  
    Even if I can't hold you right now,  
    you live in my heart every single moment.
  </p>

  <button onclick="openModal('feelings')">💖 Surprise 1</button>
  <button onclick="openModal('reasons')">🌹 Surprise 2</button>
</div>

<!-- Modal -->
<div class="modal" id="modal">
  <div class="modal-box">
    <div class="close" onclick="closeModal()">❌</div>
    <div id="modalText"></div>
  </div>
</div>

<script>
function openModal(type) {
  const modal = document.getElementById("modal");
  const text = document.getElementById("modalText");

  if (type === "feelings") {
    text.textContent = `मेरी अधूरी सी कहानी का एक पूर्ण हिस्सा हो तुम...
तुम बिन मैं अधूरा सा, तुम्हारे साथ में सब संपूर्ण।

मैं तुमसे माफी माँगता हूँ कि मैं हमेशा तुम्हारी उम्मीदों पर खरा नहीं उतर पाया,
पर यकीन मानो, जितना कर सकता हूँ पूरे दिल से तुम्हारे लिए करता हूँ।

I will always love you till the light exists in the universe ❤️

I LOVE YOU KALPANA 💝`;
  }

  if (type === "reasons") {
    text.textContent = `💯 100 Reasons Why I Love You 💯

1. Your smile
2. Your laugh
3. The way you look at me
4. How safe I feel with you
5. Your kindness
6. Your honesty
7. Your patience with me
8. The way you listen
9. You understand without words
10. Your silly side
11. Your care
12. Your loyalty
13. You remember small things
14. The way you hold my hand
15. Your voice
16. Your warmth
17. You calm my chaos
18. Your support
19. You believe in me
20. Your efforts
21. Your respect
22. Late night talks
23. Your hugs
24. You make bad days better
25. Your flaws
26. Your strengths
27. Your honesty in love
28. Your presence
29. You make time for me
30. You care silently
31. Your way of loving
32. Your happy eyes
33. You worry when I’m quiet
34. You stand by me
35. Your understanding heart
36. Your pure intentions
37. Your soft words
38. Your trust
39. Small surprises
40. Your big heart
41. You make ordinary days special
42. Your forgiveness
43. Your truth
44. You choose me
45. Your effort to stay
46. Your comforting presence
47. Your gentle care
48. You make me feel valued
49. Your emotional depth
50. Your unconditional love
51. You inspire me
52. You warm my cold days
53. Your faith in love
54. Your calmness
55. Your madness with me
56. You protect us
57. Your consistency
58. Support in my lows
59. Pride in my wins
60. You heal me
61. Patience with my flaws
62. Honesty in fights
63. Effort to understand
64. Comforting silence
65. Smile after tears
66. Love in actions
67. Thoughtful nature
68. You make me feel chosen
69. Warm words
70. Soft care in hard times
71. Presence feels like home
72. Respect my dreams
73. Love deeply
74. Your strength
75. Vulnerable with me
76. Your hope
77. Loyalty in storms
78. Gentle heart
79. Reassurance
80. You complete me
81. Honest emotions
82. Comfort in silence
83. Healing laughter
84. Love that stays
85. Trust
86. Care in little things
87. Understanding soul
88. Calm touch
89. Emotional support
90. Grow together
91. Warmth in my life
92. Love that feels real
93. Patience with time
94. Respect for us
95. Gentle reminders
96. Love that feels safe
97. You’re in my prayers
98. Heart that loves honestly
99. Soul that feels like home
100. Because you loved me more than I deserve ❤️`;
  }

  modal.style.display = "flex";
}

function closeModal() {
  document.getElementById("modal").style.display = "none";
}
</script>

</body>
</html>
