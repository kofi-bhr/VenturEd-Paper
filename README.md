# 📝 VenturEd-Paper

Heyoo! 👋 Welcome to the LaTeX project for "Invisible Sets: Measuring Policy Effectiveness with Variable Opportunity Sets" - a collaborative research paper between The Perrin Institution and VenturEd Global.

## 🚀 Getting Started

### For Setup Team (w/ LaTeX Workshop)

1. **Prerequisites**
   - Install [VS Code](https://code.visualstudio.com/) if you haven't already (this works with Cursor, Windsurf, Pear, and all forks of VSC too!)
   - Install the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension
   - Make sure you have a LaTeX distribution installed:
     - macOS: [MacTeX](https://www.tug.org/mactex/)
     - Windows: [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/)
     - Linux: [TeX Live](https://www.tug.org/texlive/)

2. **Clone this repo**
   ```bash
   git clone <repository-url>
   cd VenturEd-Paper
   ```

3. **Open in VS Code**
   ```bash
   code .
   ```

4. **Build the project**
   - Open `main-files/main.tex` in VS Code
   - Click the "Build LaTeX Project" button in the LaTeX Workshop sidebar (will be a green play button, or one that looks like 2 panels with a magnifying glass)
   - Or use the shortcut: `Ctrl+Alt+B` (Windows/Linux) or `Cmd+Alt+B` (macOS)

5. **View the PDF**
   - After building, the PDF should open automatically
   - If not, click the "View PDF" button in the LaTeX Workshop sidebar

### Troubleshooting
- Getting weird errors? Try cleaning auxiliary files and rebuilding
- Still stuck? Check if all required packages are installed. LaTeX Workshop should prompt you to install missing packages :)

## 📚 Project Structure

- **`main-files/main.tex`**: The main document that pulls everything together
- **`week-1/mathtutorial.tex`**: Math primer for the economic concepts used in the paper
- **`main.bib` & `references.bib`**: Bibliography files for citations

## 📖 What's This All About?

This paper explores the concept of "Invisible Sets" - how people's choices are constrained by options they may not even know exist! It's particularly focused on:

- How limited access to opportunities affects policy effectiveness
- The role of social networks in information distribution
- Mathematical frameworks for measuring these "invisible" constraints
- Policy implications for more equitable access

The math might look scary at first (lots of symbols!), but the `mathtutorial.tex` file breaks it down in a super approachable way. Start there if you're new to this kind of research!

## 🤝 Contributing

If you're one of our awesome RAs:

1. Make sure you understand the section you're working on (ask questions!)
2. Follow the LaTeX style conventions already in the document
3. Commit your changes with clear, descriptive messages
4. Don't worry about making mistakes - that's how we learn! :)

## 📝 Notes

- The paper uses custom theorem environments and styling - check out the preamble in `main.tex` to see how they work
- We're using a professional academic paper format, but with some extra explanations to make the content more accessible
- Feel free to add more explanatory boxes (using the `tcolorbox` environment) when introducing complex concepts

## 🙌 Credits

This research is a collaboration between:
- **The Perrin Institution**: An independent, nonpartisan think tank dedicated to advancing evidence-based policy
- **VenturEd Global**: A nonprofit organization providing first career opportunities to underrepresented talent in technology and finance

And of course, all the brilliant RAs contributing their insights and hard work!

---

Questions? Reach out to the project leads! Happy TeXing! 📊📈🧮