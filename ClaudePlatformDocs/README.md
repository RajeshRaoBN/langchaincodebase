brew install anthropics/tap/ant

ant auth login

mkdir claude-quickstart && cd claude-quickstart
python3 -m venv .venv && source .venv/bin/activate
pip install anthropic