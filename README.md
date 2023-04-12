<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
  @keyframes wave {
    0%, 60%, 100% {
      transform: translateY(0);
    }
    30% {
      transform: translateY(-10px);
    }
  }

  @keyframes jump {
    0%, 60%, 100% {
      transform: translateY(0);
    }
    30% {
      transform: translateY(-10px);
    }
  }

  h1 span {
    display: inline-block;
    animation-duration: 1.2s;
    animation-iteration-count: infinite;
  }

  h1 .emoji-wave {
    animation-name: jump;
  }

  h1 .emoji-middlefinger {
    animation-name: jump;
  }

  h1 span:nth-child(1) { animation-delay: 0.1s; }
  h1 span:nth-child(2) { animation-delay: 0.2s; }
  h1 span:nth-child(3) { animation-delay: 0.3s; }
  h1 span:nth-child(4) { animation-delay: 0.4s; }
  h1 span:nth-child(5) { animation-delay: 0.5s; }
  h1 span:nth-child(6) { animation-delay: 0.6s; }
  h1 span:nth-child(7) { animation-delay: 0.7s; }
  h1 span:nth-child(8) { animation-delay: 0.8s; }
</style>
</head>
<body>
  <div align="center">
    <table>
      <tr>
        <td valign="top" width="50%">
          <img src="https://github.com/Quinchy/Quinchy/blob/main/QuinchY.gif" alt="animated" width="100%" />
        </td>
        <td valign="top" width="50%">
          <h1>
            <span>H</span>
            <span>e</span>
            <span>l</span>
            <span>l</span>
            <span>o</span>
            <span>&nbsp;</span>
            <span>p</span>
            <span>o</span>
            <span>&nbsp;</span>
            <span class="emoji-wave">👋</span>
            <span class="emoji-middlefinger">🖕</span>
          </h1>
          <p>
            My name is Cyril James De Guzman, and I am a Computer Science student majoring in Software Development at Bataan Peninsula State University. As an aspiring full-stack developer and machine learning engineer, I primarily use Java and C# for desktop and mobile application development, while employing JavaScript for website creation. I am always open to exploring new technologies and utilizing artificial intelligence to enhance my work. Welcome to my GitHub page, where you can discover the exciting projects I am passionate about.
          </p>
        </td>
      </tr>
    </table>
  </div>
</body>
</html>
