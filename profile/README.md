<img width="4000" height="1000" alt="image" src="https://github.com/user-attachments/assets/23c29e07-893b-4c8b-8b9d-917e827d0001" />
<hr /><br />

## Welcome to Nova 👋

Nova is an AI-powered compiler and execution engine designed to eliminate syntax blockers and streamline the development workflow. 

### Why Nova?

* **Universal Syntax Tolerance:** Nova automatically interprets, corrects, and compiles diverse syntax structures.
* **Instant Execution Plans:** Describe your logic and Nova generates a verified implementation pipeline.
* **Zero Debugging Loops:** Spend less time fixing typos and more time building core features.


### Quick Start

1. Head to [groq.com](https://groq.com) and get your own API key

2. Run this install script:
```bash
cd ~
mkdir .novacompile
cd .novacompile
git clone https://github.com/novacompile/compiler.git
cd compiler
```

3. Run the setup script (have your API key read):
```bash
bash setup.sh
```

4. When your ready to compile, simply run:
```bash
nova your_script.no
```

> [!NOTE]
> To launch the shell, just run `nova`, to launch the chat agent, run `nova -c`; after you have set it up correctly. To view all flags run `nova --flags`.
