<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mindnest</title>
  <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/3.2.1/anime.min.js"></script>
  <style>
    /* Custom styles for the chill website */
    .animated-bg {
      min-height: 100vh;
      transition: all 1s;
      background: linear-gradient(-45deg, #e6eecf 0%, #a398b2 25%, #355c7d 60%, #e3eaf2 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .alt-bg {
      background: linear-gradient(-45deg, #a398b2 0%, #3a6ea5 50%, #bfcad6 100%);
      background-size: 200% 200%;
      animation: gradientBGalt 32s ease-in-out infinite;
    }

    .mauve-bg {
      background: linear-gradient(-45deg, #a398b2 0%, #b6a7c9 50%, #8c7a99 100%);
      background-size: 200% 200%;
      animation: gradientBGmauve 32s ease-in-out infinite;
    }

    .bw-mix-bg {
      background: linear-gradient(-45deg, #2c3e50 0%, #34495e 25%, #7f8c8d 50%, #95a5a6 75%, #ecf0f1 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .tech-bg {
      background: linear-gradient(-45deg, #1e3c72 0%, #2a5298 25%, #4a90e2 50%, #7bb3f0 75%, #a8d8ff 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .sunset-bg {
      background: linear-gradient(-45deg, #ff6b6b 0%, #ffa07a 25%, #ffd93d 50%, #ff8e53 75%, #ff6b9d 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .nature-bg {
      background: linear-gradient(-45deg, #2d5016 0%, #4a7c59 25%, #7fb069 50%, #a7c957 75%, #d4e157 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .corporate-bg {
      background: linear-gradient(-45deg, #1e3a8a 0%, #3b82f6 25%, #60a5fa 50%, #93c5fd 75%, #dbeafe 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .neon-bg {
      background: linear-gradient(-45deg, #ff006e 0%, #8338ec 25%, #3a86ff 50%, #06ffa5 75%, #ffbe0b 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .earth-bg {
      background: linear-gradient(-45deg, #8b4513 0%, #a0522d 25%, #cd853f 50%, #deb887 75%, #f5deb3 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .ocean-bg {
      background: linear-gradient(-45deg, #001f3f 0%, #034694 25%, #0074d9 50%, #7fdbff 75%, #b3d9ff 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .royal-bg {
      background: linear-gradient(-45deg, #4b0082 0%, #800080 25%, #9932cc 50%, #ba55d3 75%, #dda0dd 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }

    .black-silver-bg {
      background: linear-gradient(-45deg, #1a1a1a 0%, #333333 25%, #4d4d4d 50%, #666666 75%, #808080 100%);
      background-size: 200% 200%;
      animation: gradientBG 32s ease-in-out infinite;
    }