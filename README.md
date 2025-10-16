class AlaaAlkawaldehProfile {
  // 👋 About Me
  String name = "Alaa Alkawaldeh";
  String role = "AI Agents Engineer 🤖";
  String focus = "Building AI-driven systems for companies and individuals ⚙️";
  List<String> skills = [
    "💡 AI Agents Design",
    "🧠 Machine Learning & NLP",
    "🐍 Python Development",
    "⚙️ Automation & APIs",
    "💬 Prompt Engineering"
  ];

  // 🏅 Leadership & Involvement
  List<String> leadership = [
    "👩‍💼 Chair – IEEE Women in Engineering (WIE), Al Al-Bayt University",
    "💻 Vice Chair – IEEE Computer Society, Al Al-Bayt University",
    "🚀 Coordinator – Center for Excellence & Innovation, Al Al-Bayt University",
    "👩‍🏫 Trainer – Crown Prince Foundation"
  ];

  // 🔥 Highlights
  List<String> highlights = [
    "🤖 Specialized in AI Agents that automate workflows and enhance productivity",
    "💡 Passionate about AI integration for real-world impact",
    "🧠 Exploring the intersection of Intelligence, Automation, and Human Interaction",
    "📚 Continuous learner in AI frameworks, tools, and architectures"
  ];

  // 🧰 Tech Toolbox
  List<String> techToolbox = [
    "🐍 Python",
    "🔮 TensorFlow",
    "🔥 PyTorch",
    "⚡ FastAPI",
    "💻 GitHub",
    "🖥️ VS Code",
    "🐚 Bash",
    "🔧 Git",
    "🐧 Linux"
  ];

  // 📊 GitHub Stats
  Map<String, String> githubStats = {
    "Stats": "https://github-readme-stats.vercel.app/api?username=alaaalkawaldeh&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10",
    "Streak": "https://github-readme-streak-stats.herokuapp.com/?user=alaaalkawaldeh&theme=tokyonight&hide_border=true&border_radius=10"
  };

  // ⚡️ Motto
  String motto = "Empowering ideas through intelligent automation.";

  // 🌐 Connect
  String connect = "🤝 Let's connect and build the future with AI";

  // 📝 Method to display profile nicely (pseudo)
  void displayProfile() {
    print("Name: $name");
    print("Role: $role");
    print("Focus: $focus\n");
    
    print("Skills:");
    skills.forEach((s) => print("- $s"));
    
    print("\nLeadership & Involvement:");
    leadership.forEach((l) => print("- $l"));
    
    print("\nHighlights:");
    highlights.forEach((h) => print("- $h"));
    
    print("\nTech Toolbox:");
    techToolbox.forEach((t) => print("- $t"));
    
    print("\nGitHub Stats:");
    githubStats.forEach((k,v) => print("$k: $v"));
    
    print("\nMotto: \"$motto\"");
    print("\nConnect: $connect");
  }
}

