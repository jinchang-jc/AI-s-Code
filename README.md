# 天气
---
# Qwen3-235B-A22B

---

# 🌤️ 天气查询网站（HarmonyOS 风格）

一个现代风格、简洁美观的天气查询网站，支持自动定位、未来三天预报、夜间模式切换等功能，无需注册 API Key，完全基于免费公共 API 构建。

## 📌 项目亮点

- ✅ **无需 API Key**
- 📍 **自动定位当前地理位置**
- 🗓️ **未来三天天气预报**
- 🌞🌙 **夜间/日间模式切换**
- 🌬️💧🔆 **显示风速、湿度、紫外线指数等丰富信息**
- 🖥️📱 **响应式设计 - 支持桌面与移动端**
- 🌈 **HarmonyOS Next 风格 UI + Material Design**

---

## 🔧 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构 |
| CSS3 (Flexbox, Grid, Variables) | 现代化样式布局 |
| JavaScript (Fetch API) | 数据请求与动态渲染 |
| wttr.in | 免费公共天气 API |
| OpenStreetMap Nominatim API | 地理位置转城市名 |

---

## 📦 功能清单

| 功能 | 描述 |
|------|------|
| 自动定位 | 使用浏览器定位功能获取当前位置并查询天气 |
| 手动输入城市查询 | 用户可手动输入任意城市名称进行天气查询 |
| 实时天气信息 | 显示温度、描述、天气图标 |
| 更多数据展示 | 风速、湿度、紫外线指数 |
| 未来三天天气预报 | 每天最高温、最低温、天气状态及图标 |
| 夜间模式切换 | 点击按钮切换深色主题，提升夜间体验 |
| 响应式布局 | 移动端适配良好，界面自适应不同设备 |

---


## 📁 文件结构

```
天气应用
├── index.html      # 主页面
└── README.md       # 项目文档
```

> ⚠️ 所有 CSS 和 JS 已整合在 `index.html` 中，便于部署和分享。

---




## 🚀 快速开始

### 1. 下载项目

```bash
git 克隆 https://github.com/yourusername/weather-app.git
cd 天气应用
```

### 2. 本地运行

只需打开 `index.html` 文件即可直接运行：

```bash
打开 index.html    # macOS
启动 index.html   # Windows
xdg-open index.html # Linux
```

或者用 VS Code、Live Server 等工具开启本地服务器。

---



## 🌐 在线预览

你可以将此页面托管到任意静态资源平台，如：

- GitHub 页
- Vercel
- Netlify
- Surge.sh

---




##📝 注意事项

- 使用了 `wttr.in` 的 JSON 接口（无限制）
- 使用了 OpenStreetMap 的反向地理编码服务（无限制）
- 自动定位功能依赖用户授权浏览器访问地理位置权限
- 夜间模式通过 CSS 变量实现，易于扩展和定制

---





##💡 后续可扩展方向

如果你有兴趣继续开发本项目，可考虑添加如下功能：

-✅ 天气背景动画（根据天气状态切换背景图或粒子效果）
- 🕒 每小时天气预测
- 📊 天气图表展示（折线图显示温度变化）
- 🌍 多语言支持
- 🧭 网站离线缓存（Service Worker + PWA）

---



## ❤️ 贡献与反馈

欢迎提出改进建议或提交 PR，共同优化这个天气查询网站！

---



## 📚 许可证

麻省理工学院许可协议

---

# Qwen3-32B

---

# 🌤️ 天气查询网站

> 一个使用公共 API 构建的现代天气查询网站，支持自动定位、夜间模式、未来三天天气预报和丰富天气信息展示。无需注册，完全免费！

---

## ✅ 功能特点

- [x] **无 API Key**：使用 [wttr.in](https://github.com/chubin/wttr.in) 公共 API，无需注册。
- [x] **自动定位**：通过浏览器获取用户当前地理位置并显示对应城市天气。
- [x] **手动输入城市**：支持任意城市名称查询。
- [x] **未来三天天气预报**：显示每天的最高/最低温度、天气描述和图标。
- [x] **丰富的天气信息**：包括风速、湿度、紫外线指数等。
- [x] **夜间模式切换**：一键切换白天/夜间主题样式。
- [x] **响应式设计**：适配手机、平板和桌面设备。
- [x] **动画与交互**：页面加载动画、按钮 hover 效果等提升用户体验。

---

## 📁 项目结构

```
weather-app/
│
├── index.html        # 主 HTML 页面
└── README.md         # 本文件（项目说明）
```

---

## 🚀 如何运行

1. **克隆项目（可选）**

   ```bash
   git 克隆 https://github.com/yourname/weather-app.git
   cd 天气应用
   ```

2. **直接打开 ``index.html`` 文件**

   - 在浏览器中打开 `index.html` 即可运行。

3. **部署到 Web 服务器（可选）**

   - 可以将整个项目上传到 GitHub Pages、Netlify、Vercel 等平台进行在线访问。

---



## 🧠 技术栈

| 技术 | 用途 |
|------|------|


| HTML5 + CSS3 | 页面结构与样式 |




---



##🛠️ 使用方法

1. 打开网页后，会默认自动检测你的地理位置，并显示该城市的天气。
2. 你也可以在搜索框中输入其他城市名称进行查询。
3. 点击右上角的“🌙”按钮可切换夜间模式。

---



##📝 注意事项

- 由于使用的是 **第三方 API**，请确保网络畅通。
- 如果无法获取当前位置，请手动输入城市名。
- 若页面加载缓慢，可能因为 API 响应延迟，建议稍后再试。

---



## 📦 扩展建议（可选）

你可以继续扩展此项目，添加如下功能：

- 多语言支持（中/英）
- 天气预警提示
- 每日天气趋势图（折线图）
- 天气背景动态变化（晴天/雨天/雪天）
- 天气提醒通知功能（需后端支持）

---


## 📬 联系方式

如有问题或建议，欢迎联系我

---



## 📎 许可证

该项目采用 MIT 开源协议，你可以自由使用、修改和分发本项目代码。

---




## ❤️ 致谢

感谢以下开源项目的支持：

- [wttr.in](https://github.com/chubin/wttr.in) —— 提供强大的天气数据服务。
- [OpenStreetMap Nominatim](https://nominatim.org/) —— 提供地理定位反向解析服务。
- HarmonyOS Next 设计风格参考 —— 提供视觉灵感。

---




# Qwen2.5-72B

# 天气查询项目

这是一个使用公共 API 构建的天气查询网站，具备自动定位、未来三天天气预报、夜间模式切换等功能。项目使用了 `wttr.in` 公共天气 API 和 OpenStreetMap 的 Nominatim 服务来获取地理位置信息。

## 功能特点

- **自动定位当前地理位置**：使用浏览器的地理位置 API 自动获取用户所在城市并显示天气信息。
- **未来三天天气预报**：显示未来三天的天气预报，包括最高温度、最低温度、天气描述和图标。
- **夜间模式切换**：提供夜间模式切换按钮，动态改变页面主题。
- **丰富的天气信息**：显示当前的温度、天气描述、风速、湿度和紫外线指数。
- **现代设计**：采用渐变背景、圆角按钮、输入框聚焦效果等，使界面更加美观。

## 技术栈

- **HTML**: 结构化标记语言。
- **CSS**: 样式设计，包括响应式布局和夜间模式切换。
- **JavaScript**: 功能实现，包括自动定位、天气查询、夜间模式切换等。
- **API**:
  - **wttr.in**: 获取天气信息。
  - **OpenStreetMap Nominatim**: 将经纬度转换为城市名称。

## 项目结构

```
weather-query/
│
├── index.html          # 主页面文件
├── styles.css          # 样式文件
└── script.js           # 脚本文件
```

## 使用方法

1. **克隆项目**：
   ```bash
   git clone https://github.com/yourusername/weather-query.git
   cd weather-query
   ```

2. **运行项目**：
   - 直接在浏览器中打开 `index.html` 文件。
   - 或者使用本地服务器（如 `http-server`）运行：
     ```bash
     npm install -g http-server
     http-server
     ```
   - 访问 `http://localhost:8080` 查看项目。

## 代码说明

### HTML (index.html)

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>天气查询 - 公共API</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>🌤️ 天气查询</h1>
        <form id="weatherForm">
            <input type="text" id="cityInput" placeholder="请输入城市名称" required>
            <button type="submit">查询</button>
        </form>
        <div id="weatherResult" class="weather-card">
            <h2 id="cityName"></h2>
            <p id="temperature"></p>
            <p id="description"></p>
            <p id="windSpeed"></p>
            <p id="humidity"></p>
            <p id="uvIndex"></p>
            <img id="weatherIcon" class="weather-icon" src="" alt="天气图标">
            <div class="forecast" id="forecast"></div>
        </div>
    </div>
    <div class="night-mode" onclick="toggleNightMode()">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M21 12a9 9 0 1 1-6.218-8.56L12 3l-.782 1.44A9 9 0 0 1 21 12zM3 17a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-2z"/></svg>
    </div>
    <script src="script.js"></script>
</body>
</html>
```

### CSS (styles.css)

```css
:root {
    --primary-color: #4a90e2;
    --bg-light: #f5f5f5;
    --text-dark: #333;
    --card-bg: #ffffff;
    --night-bg: #1a1a1a;
    --night-text: #ffffff;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background: var(--bg-light);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 2rem;
    transition: background 0.3s ease;
}

.container {
    max-width: 450px;
    width: 100%;
    background-color: var(--card-bg);
    padding: 2rem;
    border-radius: 16px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.05);
    text-align: center;
    transition: all 0.3s ease-in-out;
}

h1 {
    font-size: 1.8rem;
    color: var(--text-dark);
    margin-bottom: 1.5rem;
}

form {
    display: flex;
    gap: 1rem;
    justify-content: center;
    margin-bottom: 2rem;
}

input[type="text"] {
    flex: 1;
    padding: 12px 16px;
    border: 1px solid #ddd;
    border-radius: 8px;
    font-size: 1rem;
    outline: none;
    transition: border-color 0.3s ease;
}

input:focus {
    border-color: var(--primary-color);
}

button {
    padding: 12px 20px;
    background-color: var(--primary-color);
    color: white;
    border: none;
    border-radius: 8px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #357ae8;
}

#weatherResult {
    display: none;
    animation: fadeIn 0.5s ease;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
}

.weather-card {
    margin-top: 1rem;
    padding: 1rem;
    background-color: #f0f8ff;
    border-radius: 12px;
    color: var(--text-dark);
}

.weather-icon {
    width: 64px;
    height: 64px;
    margin: 1rem auto;
    filter: drop-shadow(0 0 5px rgba(0,0,0,0.1));
}

.forecast {
    margin-top: 1rem;
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
}

.forecast-item {
    background-color: #f0f8ff;
    padding: 1rem;
    border-radius: 12px;
    flex: 1 1 calc(33.333% - 1rem);
    text-align: center;
}

.forecast-item h3 {
    margin-bottom: 0.5rem;
}

.forecast-item p {
    margin: 0.25rem 0;
}

.night-mode {
    position: fixed;
    top: 1rem;
    right: 1rem;
    padding: 0.5rem 1rem;
    background-color: var(--primary-color);
    color: white;
    border-radius: 8px;
    cursor: pointer;
    z-index: 1000;
}

.night-mode:hover {
    background-color: #357ae8;
}

.night-mode svg {
    width: 16px;
    height: 16px;
    fill: white;
}

@media (max-width: 500px) {
    form {
        flex-direction: column;
        align-items: stretch;
    }
}
```

### JavaScript (script.js)

```javascript
let isNightMode = false;

function toggleNightMode() {
    isNightMode = !isNightMode;
    document.documentElement.style.setProperty('--bg-light', isNightMode ? '#1a1a1a' : '#f5f5f5');
    document.documentElement.style.setProperty('--text-dark', isNightMode ? '#ffffff' : '#333333');
    document.documentElement.style.setProperty('--card-bg', isNightMode ? '#2a2a2a' : '#ffffff');
    document.documentElement.style.setProperty('--text-light', isNightMode ? '#bfbfbf' : '#777777');
    document.body.style.backgroundColor = isNightMode ? '#1a1a1a' : 'linear-gradient(135deg, #e6f7ff, #f5f5f5)';
    document.querySelector('.night-mode svg').setAttribute('fill', isNightMode ? '#ffffff' : '#333333');
}

function getWeather(city) {
    const url = `https://wttr.in/${encodeURIComponent(city)}?format=j1`;

    fetch(url)
        .then(response => response.json())
        .then(data => {
            if (!data || data.nearest_area.length === 0) {
                alert("未找到该城市的天气信息，请检查输入是否正确。");
                return;
            }

            const currentCondition = data.current_condition[0];
            const cityName = data.nearest_area[0].areaName[0].value;
            const temperature = currentCondition.temp_C;
            const description = currentCondition.weatherDesc[0].value;
            const windSpeed = currentCondition.windspeedKmph;
            const humidity = currentCondition.humidity;
            const uvIndex = currentCondition.uvIndex;
            const iconUrl = `https:${currentCondition.weatherIconUrl[0].value}`;

            document.getElementById('cityName').textContent = cityName;
            document.getElementById('temperature').textContent = `温度: ${temperature}°C`;
            document.getElementById('description').textContent = `描述: ${description}`;
            document.getElementById('windSpeed').textContent = `风速: ${windSpeed} km/h`;
            document.getElementById('humidity').textContent = `湿度: ${humidity}%`;
            document.getElementById('uvIndex').textContent = `紫外线指数: ${uvIndex}`;
            document.getElementById('weatherIcon').src = iconUrl;

            document.getElementById('weatherResult').style.display = 'block';

            // 未来三天天气预报
            const forecastContainer = document.getElementById('forecast');
            forecastContainer.innerHTML = '';
            const forecastData = data.weather;

            forecastData.forEach(day => {
                const date = day.date;
                const maxTemp = day.maxtempC;
                const minTemp = day.mintempC;
                const condition = day.hourly[0].weatherDesc[0].value;
                const iconUrl = `https:${day.hourly[0].weatherIconUrl[0].value}`;

                const forecastItem = document.createElement('div');
                forecastItem.classList.add('forecast-item');
                forecastItem.innerHTML = `
                    <h3>${date}</h3>
                    <p>最高温度: ${maxTemp}°C</p>
                    <p>最低温度: ${minTemp}°C</p>
                    <p>天气: ${condition}</p>
                    <img src="${iconUrl}" alt="天气图标" class="weather-icon">
                `;
                forecastContainer.appendChild(forecastItem);
            });
        })
        .catch(error => {
            console.error('请求失败:', error);
            alert('无法获取天气数据，请稍后再试。');
        });
}

document.getElementById('weatherForm').addEventListener('submit', function(event) {
    event.preventDefault();
    const city = document.getElementById('cityInput').value;
    getWeather(city);
});

// 自动定位当前地理位置
if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(position => {
        const latitude = position.coords.latitude;
        const longitude = position.coords.longitude;
        const url = `https://nominatim.openstreetmap.org/reverse.php?format=json&lat=${latitude}&lon=${longitude}`;

        fetch(url)
            .then(response => response.json())
            .then(data => {
                const city = data.address.city || data.address.town;
                if (city) {
                    document.getElementById('cityInput').value = city;
                    getWeather(city);
                } else {
                    alert("无法获取当前位置的城市信息。");
                }
            })
            .catch(error => {
                console.error('位置获取失败:', error);
                alert('无法获取当前位置，请手动输入城市。');
            });
    }, error => {
        console.error('位置获取失败:', error);
        alert('无法获取当前位置，请手动输入城市。');
    });
} else {
    alert('您的浏览器不支持地理位置定位。');
}

// 页面加载时自动查询杭州
window.onload = function() {
    document.getElementById('cityInput').value = '杭州';
    getWeather('杭州');
};
```

## 问题反馈

如果在使用过程中遇到任何问题或有任何改进建议，欢迎提 Issue 或 Pull Request。

## 许可证

本项目采用 MIT 许可证，详情见 [LICENSE](LICENSE) 文件。

## 致谢

感谢以下项目的贡献和支持：

- [wttr.in](https://wttr.in) - 免费公共天气 API
- [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org) - 地理位置转换服务
- [GitHub](https://github.com) - 代码托管平台

---

```

---



