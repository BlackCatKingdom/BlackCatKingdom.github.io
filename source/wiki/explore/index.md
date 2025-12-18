{% okr %}
o1:
  title: 🌟 2026 年度核心目标
  note: 对应截图里的 "O1"
  status: in_track      # 蓝色：正常
  value: 45
  items:
    kr1:                # 关键修改：用 kr1 代替 "-"，就会显示 KR1 标签
      title: 📚 阅读 20 本书籍
      value: 30
      status: in_track  # 蓝色：正常
    kr2:                # 关键修改：用 kr2 显示 KR2 标签
      title: 🏃‍♂️ 累计跑步 500 公里
      value: 10
      status: off_track # 橙色：延期 (对应截图里的效果)
    kr3:
      title: 📝 博客更新 50 篇优质文章
      value: 100
      status: finished  # 绿色：已完成
o2:
  title: 💻 技术能力提升
  note: 对应截图里的 "O2"
  status: in_track
  value: 80
  items:
    kr1:
      title: 掌握 Vue3 和 Hexo 原理
      value: 100
      status: finished
    kr2:
      title: 开发一个开源小工具
      value: 20
      status: in_track
{% endokr %}