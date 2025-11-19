# 🎣 Phishing Net

**Community tool to investigate suspicious websites from dating scams, phishing attempts, and online fraud.**

## 🎯 Purpose

Everyone who dates online has dealt with suspicious profiles, fake websites, and potential scammers. **Phishing Net** helps you investigate questionable domains by looking up their registration information automatically.

This tool is designed to help identify cyber criminals by revealing:
- Domain owner information
- Registrar details
- Country of registration
- Registration date
- Contact information (when publicly available)

## 🚀 How to Use

### Option 1: Manual Lookup (Recommended)

1. Go to the **[Actions](../../actions/workflows/website-lookup.yml)** tab
2. Click **"Run workflow"**
3. Enter the suspicious website URL (e.g., `suspicious-dating-site.com`)
4. Click **"Run workflow"** button
5. Wait a few seconds for the action to complete
6. View the results in the workflow run logs

### Option 2: Report via Issue

You can also create an issue to report a suspicious website, and the workflow will automatically run.

## 📊 What Information You'll Get

The lookup will provide:
- **Domain Owner**: Who registered the domain
- **Registrar**: Which company the domain was registered through
- **Registration Date**: When the domain was first registered (newly registered domains are often red flags)
- **Country**: Where the domain was registered
- **Contact Info**: Public WHOIS data (if not privacy-protected)

## ⚠️ Common Red Flags

When investigating suspicious websites, watch for:
- **Very new domains** (registered within the last few months)
- **Privacy-protected registration** (hides owner info)
- **Mismatched locations** (claims to be in US but registered elsewhere)
- **Suspicious registrars** (known for hosting fraudulent sites)
- **Similar domains** to legitimate sites (typosquatting)

## 🛡️ Safety Tips for Online Dating

1. **Never send money** to someone you haven't met in person
2. **Be suspicious of urgent requests** ("emergency", "stuck abroad", etc.)
3. **Video chat** before meeting to verify identity
4. **Google image search** profile photos to check for stolen images
5. **Check domains** of any websites they send you
6. **Meet in public places** for first meetings

## 🤝 Contributing

Found this tool helpful? Consider:
- ⭐ Starring this repository
- 🐛 Reporting issues or suspicious patterns you've noticed
- 📝 Suggesting improvements
- 🔗 Sharing with others who might benefit

## ⚖️ Legal & Ethical Use

This tool uses publicly available WHOIS data. Please use responsibly:
- ✅ Investigating suspicious websites sent to you
- ✅ Protecting yourself from potential scams
- ✅ Reporting findings to authorities when appropriate
- ❌ Harassment or doxxing
- ❌ Violating privacy laws
- ❌ Using info for malicious purposes

## 📞 Need Help?

If you believe you've been scammed:
- 🇺🇸 Report to [FBI IC3](https://www.ic3.gov/)
- 💔 Report romance scams to [FTC](https://reportfraud.ftc.gov/)
- 🌐 Report to your local law enforcement

## 📄 License

MIT License - See [LICENSE](LICENSE) file for details

---

**Stay safe online! 🛡️**
