# 🧬 Genesis - Web-Based Password Generator

**Genesis** is a sleek, web-based password list generator designed for penetration testers, security researchers, and enthusiasts. With just a few keywords, you can generate highly complex and effective wordlists using smart mutation and combination logic — all within your browser.

**No installation required. No server interaction. 100% client-side.**

---

##  Features

### Dual Generation Modes

- **Automated Mode**  
  Quickly generate effective password lists with smart default mutations. Just input a keyword and click.

- **Advanced Mode**  
  Unfold the **Advanced Configuration** panel to customize your generation logic — similar to command-line tools like `crunch` or `psudohash`.

---

### Powerful Mutation Engine

- **Character Substitution**  
  Swap letters with common leet-style substitutions (e.g., `a → @`, `s → $`, etc.)

- **Case Variation**  
  Mix and match upper/lowercase variations for maximum coverage.

- **Number & Year Appending**  
  Append sequences like `123`, or years like `1998`, `2024`, etc., in multiple formats.

- **Custom Padding**  
  Prefix or suffix your keywords with common or custom symbols (e.g., `!`, `@#`, `321`).

- **Keyword Combination**  
  Combine multiple keywords in various permutations using custom separators. *(Advanced Mode)*

---

### 🔒 Browser-Based & Secure

- **No Installation Required**  
  Just open the HTML file — no Python, no dependencies.

- **Client-Side Only**  
  Everything runs in your browser. Your input never leaves your machine.

- **Built-in Safety Cap**  
  Limits output to **50,000 passwords** per session to prevent browser slowdowns or crashes.


2. **Choose Your Mode**  
   - For a quick list, hit **Generate Passwords**
   - For full control, open **Advanced Configuration** and customize your settings

3. **Generate & Download**  
   - Click **Generate**
   - Wait for results (previewed in the text area)
   - Click **Download .txt** to export your wordlist

---

## Credit

This web app is inspired by the excellent [psudohash](https://github.com/t3l3machus/psudohash) CLI tool created by [Panagiotis Chartas (t3l3machus)](https://github.com/t3l3machus).

Genesis is a modern, browser-based reimplementation that aims to bring the same power to a graphical interface.

---

## 📂 Repository Structure

