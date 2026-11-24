# langchaincodebase

uv tool install managed-deepagents

mda init research-assistant
cd research-assistant
uv sync

pip install "pydantic-ai-slim[google]"
export GOOGLE_API_KEY="your-api-key"

mda dev
mda deploy