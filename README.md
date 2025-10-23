# ASO Optimizer - Claude Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude](https://img.shields.io/badge/Claude-Skill-blue)](https://claude.ai)

> A comprehensive App Store Optimization (ASO) toolkit for Claude that helps developers optimize their iOS and Android apps with intelligent keyword research, competitor analysis, and multi-language localization.

## 🎯 What is this?

ASO Optimizer is a custom Claude skill that transforms Claude into an ASO expert assistant. It guides you through the entire ASO workflow—from keyword discovery to final metadata optimization—using proven strategies and automated competitor research.

Perfect for:
- 📱 Independent app developers
- 🚀 Startups launching new apps
- 🌍 Teams localizing for multiple markets
- 🔄 Anyone looking to improve their ASO strategy

## ✨ Features

### 🔍 Intelligent Keyword Research
- Semantic analysis of your app description
- User intent mapping (navigational, informational, transactional)
- Long-tail keyword generation
- Keyword prioritization and tiering (Tier 1/2/3)

### 🎯 Competitor Analysis
- Automated web search for top competitors
- Keyword extraction from competitor metadata
- Competitive gap analysis
- Positioning and differentiation insights

### 📝 Metadata Optimization
- iOS App Store: App Name (30), Subtitle (30), Keywords (100)
- Google Play: Title (30), Short Description (80), Long Description (4000)
- Character count validation
- Platform-specific best practices

### 🌍 Multi-Language Localization
- Keyword translation with cultural adaptation
- Local competitor research per market
- Localized metadata generation
- Side-by-side comparison matrices

### 📊 Deliverables
- **Markdown Reports**: Complete analysis with recommendations
- **Excel Spreadsheets**: Keyword inventory, competitor tracking, performance templates
- **Ready-to-use metadata**: Copy-paste optimized content

## 🚀 Installation

### Prerequisites
- Access to [Claude.ai](https://claude.ai) (with custom skills support)

### Steps

1. **Download the skill**
   ```bash
   # Clone this repository
   git clone https://github.com/yourusername/aso-optimizer-skill.git
   
   # Or download the latest release
   # https://github.com/yourusername/aso-optimizer-skill/releases
   ```

2. **Install in Claude**
   - Go to [claude.ai](https://claude.ai)
   - Click the tools icon (bottom left)
   - Select "Skills"
   - Click "Upload custom skill"
   - Upload `aso-optimizer.zip`

3. **Start using**
   - The skill activates automatically when discussing ASO
   - Or explicitly say: "Use the ASO Optimizer skill"

## 💡 Usage

### Quick Start

Simply describe your app to Claude:

```
"I have a photo editing app called PhotoMax with filters, collage tools, 
and background removal. It's for Instagram users. Help me with ASO."
```

Claude will:
1. Ask clarifying questions
2. Generate 50+ relevant keywords
3. Analyze competitors
4. Create optimized metadata
5. Deliver a complete ASO package

### Example Workflows

#### 1️⃣ Complete ASO from Scratch
```
You: "Help me optimize ASO for my fitness tracking app on iOS"

The skill will:
- Generate comprehensive keyword list
- Research top fitness app competitors
- Create optimized App Name, Subtitle, and Keywords field
- Provide a ready-to-use ASO report
```

#### 2️⃣ Competitor Analysis Only
```
You: "Analyze competitors for my budget tracking app"

The skill will:
- Search for top budget apps
- Extract their ASO strategies
- Identify keyword gaps and opportunities
- Create competitive intelligence report
```

#### 3️⃣ Multi-Language Localization
```
You: "Localize my app for Italian and Spanish markets"

The skill will:
- Research local competitors
- Adapt keywords culturally
- Generate localized metadata
- Create comparison matrix
```

#### 4️⃣ Keyword Refresh
```
You: "My current keywords aren't working: photo,edit,filter,camera"

The skill will:
- Analyze your current keywords
- Compare with competitor keywords
- Suggest specific improvements
- Prioritize changes by impact
```

## 📚 What's Included

```
aso-optimizer/
├── SKILL.md                          # Main skill orchestration file
├── references/
│   ├── store-guidelines.md           # iOS & Android ASO best practices
│   ├── keyword-strategies.md         # Keyword research techniques
│   └── competitor-analysis.md        # Competitor research framework
├── README.md                         # This file
└── LICENSE                           # MIT License
```

## 🎓 How It Works

The skill follows a proven ASO workflow:

1. **Information Gathering** → Understand your app and goals
2. **Keyword Research** → Generate relevant keywords using multiple techniques
3. **Competitor Analysis** → Research top apps using web search
4. **Metadata Optimization** → Create optimized content for each platform
5. **Localization** → Adapt for different markets (if needed)
6. **Delivery** → Provide actionable reports and spreadsheets

## 🔧 Advanced Features

### Character Limit Validation
Automatically validates all metadata against platform limits:
- iOS: 30/30/100 characters
- Android: 30/80/4000 characters

### ASO Best Practices
Built-in knowledge of:
- Keyword stuffing avoidance
- Competitor brand name restrictions
- Conversion optimization
- Platform-specific guidelines

### Integration
Works seamlessly with other Claude skills:
- **xlsx skill**: For creating tracking spreadsheets
- **docx skill**: For formal client reports
- **web_search**: For competitor intelligence (automatic)

## 📖 Documentation

### Keyword Strategies
The skill includes comprehensive keyword research methodologies:
- Semantic analysis and expansion
- User intent mapping
- Competitive keyword mining
- Category-specific patterns
- Multi-language considerations

### Store Guidelines
Complete reference for both platforms:
- Character limits and formatting
- Screenshot optimization
- Conversion best practices
- Universal ASO principles

### Competitor Analysis
Systematic framework for competitive intelligence:
- Data collection processes
- Web search strategies
- Gap analysis techniques
- Positioning insights

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Issues**: Found a bug? [Open an issue](https://github.com/yourusername/aso-optimizer-skill/issues)
2. **Suggest Features**: Have an idea? Share it in discussions
3. **Improve Documentation**: Submit PRs for better docs
4. **Share Use Cases**: Tell us how you're using it!

### Development

To modify the skill:

1. Edit files in the skill directory
2. Test with Claude
3. Package using the skill-creator scripts:
   ```bash
   python3 scripts/package_skill.py /path/to/aso-optimizer
   ```
4. Submit a pull request

## 📊 Use Cases

### For Independent Developers
- Quick ASO for side projects
- Competitive research on a budget
- Multi-platform optimization
- International market expansion

### For Agencies
- Client ASO audits
- Competitive intelligence reports
- Localization at scale
- ASO strategy documentation

### For Teams
- Standardized ASO workflows
- Knowledge sharing
- Onboarding new team members
- Consistent deliverables

## ⚠️ Limitations

- Relies on web search for competitor data (public information only)
- Cannot access real-time App Store rankings
- Keyword volume estimates are qualitative, not quantitative
- Results depend on Claude's current knowledge (training data + search)

## 🛠 Troubleshooting

**Q: Skill not activating?**
- Try saying "Use the ASO Optimizer skill" explicitly
- Check that the skill is properly uploaded in Claude settings

**Q: Competitor analysis not finding apps?**
- Make sure you provide specific competitor names or categories
- Try more specific search terms

**Q: Character limits not working?**
- Report as a bug—the skill should always validate limits

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Free to use, modify, and distribute for personal and commercial projects.

## 🙏 Acknowledgments

- Built for the Claude Skills ecosystem
- Inspired by best practices from ASO experts
- Community feedback and contributions

## 📧 Contact

- **Issues**: [GitHub Issues](https://github.com/yourusername/aso-optimizer-skill/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/aso-optimizer-skill/discussions)

## ⭐ Support

If this skill helps your ASO efforts, please:
- Star this repository
- Share with other developers
- Contribute improvements
- Report your success stories!

---

**Made with ❤️ for the indie developer community**

Happy optimizing! 🚀
