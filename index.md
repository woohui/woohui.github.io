---
layout: page
title: About Me
date: <%= Time.now.strftime('%Y-%m-%d %H:%M:%S') %>
---

# About Me
---
<!-- <img src="./images/Life_Photo.JPG!min" class="floatpic"> -->

Here is **Wu Hui**.<br>

I am a PhD student at the College of Economics and Management, **Huazhong Agricultural University**. There are **<i id="timer">\*\*\*</i>** days remaining.

---

## Research Interests

**<font color="#990000"></font>**


- Novel Business Model
- Low Carbon

My current research focuses on the practical challenges that **game theory** encounters in real-life situations.

---

## Contact me

- Mail: woohui [at] vip.qq.com
- Website: [https://wuhui.de](https://wuhui.de)

<script>
  // 目标日期：2027年6月30日
  const targetDate = new Date(2027, 5, 30); // 注意：月份是从0开始的，所以6月是5

  // 当前时间
  const now = new Date();

  // 计算时间差（以毫秒为单位）
  const timeDiff = targetDate - now;

  // 将毫秒转换为天数
  const daysDiff = Math.floor(timeDiff / (1000 * 60 * 60 * 24));

  // 输出结果
  document.getElementById('timer').innerHTML = daysDiff;
</script>
