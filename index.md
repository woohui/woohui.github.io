---
layout: page
---

# About Me
---
<!-- <img src="./images/Life_Photo.JPG" class="floatpic"> -->

Here is **Hui Wu**.<br>

I am a PhD student at the College of Economics and Management, Huazhong Agricultural University. Previously, I worked at Guangdong University of Science and Technology.

---

## Research Interests

**<font color="#990000"></font>**


- Novel Business Model
- Low Carbon

My current research focuses on the practical challenges that **game theory** encounters in real-life situations.

---

## News and Updates

- Dec 19, 2024：The first paper of my doctoral phase has been completed and submitted for publication🥰.
- **Dec 20, 2024**：Desk Rejected by AE 😭.
- Dec 21, 2024: Submit the paper to another marketing journal . Kindly consider it favorably.

---

## What to Expect
<div class="countdown">
    <h1>Countdown to June 30, 2027</h1>
    <p id="timer">Calculating...</p>
</div>

<script>
    // 优化倒计时逻辑
    document.addEventListener('DOMContentLoaded', function () {
        const targetDate = new Date('{{ target_date | default: "2027-06-30T00:00:00" }}');
        const timerElement = document.getElementById('timer');

        function updateCountdown() {
            const now = new Date();
            const diff = targetDate - now;

            if (diff <= 0) {
                timerElement.textContent = "The countdown is over!";
                clearInterval(intervalId);
                return;
            }

            const days = Math.floor(diff / (1000 * 60 * 60 * 24));
            timerElement.innerHTML = `Victory is just ahead, <strong>${days} days</strong> to go.`;
        }

        // 提前显示占位内容，增强用户体验
        timerElement.textContent = "Loading ...";

        // 定时更新
        const intervalId = setInterval(updateCountdown, 1000);
        updateCountdown(); // 即刻执行一次，避免等待首个间隔
    });
</script>

