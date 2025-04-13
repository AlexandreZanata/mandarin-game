# mandarin-game
WordQuest – A fun and interactive vocabulary game to help users learn English through translation challenges, example sentences, and audio pronunciation. Built with HTML, CSS, JavaScript, and modern UI libraries.

# WordQuest Plus - 汉语词汇学习游戏 (Mandarin Vocabulary Learning Game)

## 📝 游戏介绍 (Game Description)
WordQuest Plus 是一款创新的网页游戏，专门为汉语学习者设计，通过游戏化方式高效记忆词汇。主要功能包括：

- 6大主题分类，超过500个实用词汇
- 3种难度级别适应不同水平学习者
- 拼音标注和发音功能帮助正确学习
- 例句展示词汇真实用法
- 智能复习系统强化记忆

## 🎮 游戏玩法 (Gameplay Instructions)

1. **开始准备** (Setup):
   - 点击"开始游戏"按钮进入
   - 选择适合的难度级别：初级/中级/高级
   - 挑选感兴趣的主题或选择"全部"随机混合
   - 确认选择开始挑战

2. **答题环节** (Answering Questions):
   - 每个问题会显示英文单词和4个中文选项
   - 点击选择你认为正确的中文翻译
   - 使用"发音"按钮听取标准普通话读音
   - 快速正确回答可获得额外时间奖励

3. **成绩报告** (Results):
   - 完成所有题目后查看详细得分报告
   - 系统会自动标记错误词汇供重点复习
   - 可随时重新开始挑战更高分数

## ⚙️ 自定义设置 (Customization Options)

### 词汇库扩展 (Vocabulary Expansion)
开发者可以通过编辑代码中的词汇数据库来增加内容，结构示例如下：

```javascript
// 食物主题-初级难度示例
food: {
    easy: [
        { 
            pt: "apple", 
            en: "苹果 (píng guǒ)", 
            exemplo: "I eat an 苹果 every morning. (我每天早上吃一个苹果。)" 
        },
        // 可继续添加更多词汇...
    ]
}
```

### 游戏参数调整 (Game Parameters)
- 题目数量：修改`shuffled.slice(0, 20)`中的数字
- 答题时间：调整`timeLeft`的初始值(秒)
- 计分规则：在`calculatePoints()`函数中自定义

### 界面个性化 (UI Customization)
1. 主题颜色：修改CSS中的`--primary`等变量值
2. 新增主题：添加类似`.theme-yourtheme`的样式类
3. 动画效果：调整`@keyframes`相关参数

## 🌐 技术实现 (Technical Implementation)
- 前端：HTML5, CSS3, JavaScript ES6
- 语音：Web Speech API中文合成
- 图标：Font Awesome 6.4
- 字体：Google Poppins

## 📜 版权声明 (License Information)
本项目采用MIT开源协议，允许自由使用和修改。

---

# WordQuest Plus - Mandarin Learning Game

## 📝 Game Description
WordQuest Plus is an innovative web-based game specifically designed for Mandarin learners to memorize vocabulary effectively through gamification. Key features include:

- 6 thematic categories with 500+ practical words
- 3 difficulty levels for different proficiency levels
- Pinyin annotation and pronunciation function
- Example sentences demonstrating word usage
- Intelligent review system to reinforce memory

## 🎮 Gameplay Instructions

1. **Setup**:
   - Click "Start Game" to begin
   - Select appropriate difficulty: Beginner/Intermediate/Advanced
   - Choose preferred theme or "All" for random mix
   - Confirm selection to start challenge

2. **Answering Questions**:
   - Each question shows an English word with 4 Chinese options
   - Click to select the correct Chinese translation
   - Use "Pronounce" button to hear standard Mandarin pronunciation
   - Fast correct answers earn time bonuses

3. **Results**:
   - View detailed score report after completion
   - System automatically flags incorrect words for review
   - Restart anytime to challenge higher scores

## ⚙️ Customization Options

### Vocabulary Expansion
Developers can expand content by editing the vocabulary database in code:

```javascript
// Food theme - Beginner level example
food: {
    easy: [
        { 
            pt: "apple", 
            en: "苹果 (píng guǒ)", 
            exemplo: "I eat an 苹果 every morning. (我每天早上吃一个苹果。)" 
        },
        // Add more words...
    ]
}
```

### Game Parameters
- Question count: Modify number in `shuffled.slice(0, 20)`
- Answer time: Adjust initial `timeLeft` value (seconds)
- Scoring: Customize in `calculatePoints()` function

### UI Customization
1. Theme colors: Modify CSS variables like `--primary`
2. New themes: Add classes like `.theme-yourtheme`
3. Animations: Adjust `@keyframes` parameters

## 🌐 Technical Implementation
- Frontend: HTML5, CSS3, JavaScript ES6
- Speech: Web Speech API Chinese synthesis
- Icons: Font Awesome 6.4
- Fonts: Google Poppins

## 📜 License Information
This project uses MIT open source license, allowing free use and modification.
