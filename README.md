
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Galeria de Ícones com Hover</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff;
            text-align: center;
            padding: 40px;
        }
        .icon-container {
            display: flex;
            overflow-x: auto;
            gap: 30px;
            padding: 20px;
        }
        .icon-box {
            flex: 0 0 auto;
            width: 120px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .icon-box:hover {
            transform: scale(1.2);
            box-shadow: 0 8px 16px rgba(0,0,0,0.3);
            z-index: 1;
        }
        .icon-box img {
            width: 64px;
            height: 64px;
        }
        .icon-label {
            margin-top: 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <h1>🧊 Desenvolvimento de Software</h1>
    <p>🔍 Desvendando o mundo da programação.</p>
    <p>🌐 Visite o repositório de <a href="https://github.com/euFabricio/Hello-world">Hello, World!</a></p>

    <h2>💻 Principais tecnologias:</h2>
    <div class="icon-container">
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" alt="VSCode">
            <div class="icon-label">VSCode</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/powershell/powershell-original.svg" alt="PowerShell">
            <div class="icon-label">PowerShell</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/windows8/windows8-original.svg" alt="Windows">
            <div class="icon-label">Windows</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" alt="GitHub">
            <div class="icon-label">GitHub</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python">
            <div class="icon-label">Python</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker">
            <div class="icon-label">Docker</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" alt="Linux">
            <div class="icon-label">Linux</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azure/azure-original.svg" alt="Azure">
            <div class="icon-label">Azure</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" alt="C#">
            <div class="icon-label">C#</div>
        </div>
        <div class="icon-box">
            <img src="https://img.icons8.com/?size=154&id=D5nuxA0qwo6w&format=png" alt="Intune">
            <div class="icon-label">Intune</div>
        </div>
        <div class="icon-box">
            <img src="https://www.svgrepo.com/show/331760/sql-database-generic.svg" alt="SQL">
            <div class="icon-label">SQL</div>
        </div>
        <div class="icon-box">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dot-net/dot-net-original.svg" alt=".NET">
            <div class="icon-label">.NET</div>
        </div>
        <div class="icon-box">
            <img src="https://www.svgrepo.com/show/354202/dotnet.svg" alt=".NET Framework">
            <div class="icon-label">.NET Framework</div>
        </div>
        <div class="icon-box">
            <img src="https://img.icons8.com/color/96/azure-devops.png" alt="Azure DevOps">
            <div class="icon-label">Azure DevOps</div>
        </div>
    </div>

    <h3>
      👋 Conecte-se comigo:&nbsp;
      <a href="https://www.linkedin.com/in/fabriciovianaribeiro/">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg" alt="LinkedIn" align="center" width="40">
      </a>
    </h3>
</body>
</html>
