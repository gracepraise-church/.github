
<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Heaven glow -->
    <radialGradient id="halo" cx="50%" cy="35%" r="55%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.9"/>
      <stop offset="40%" stop-color="#ffd37a" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
    </radialGradient>

    <!-- Soft glow -->
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="6"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="220" fill="#0b1220"/>

  <!-- Heavenly light -->
  <circle cx="600" cy="80" r="260" fill="url(#halo)" filter="url(#softGlow)"/>

  <!-- Title -->
  <text x="600" y="105"
        text-anchor="middle"
        font-size="44"
        fill="#ffffff"
        font-family="Segoe UI, Helvetica, Arial, sans-serif"
        font-weight="700">
    Grace and Praise Bangladeshi Church
  </text>

  <!-- Subtitle -->
  <text x="600" y="150"
        text-anchor="middle"
        font-size="20"
        fill="#f6e6b8"
        font-family="Segoe UI, Helvetica, Arial, sans-serif">
    A Spiritual Hearth on Earth · A Window Toward Heaven
  </text>
</svg>
