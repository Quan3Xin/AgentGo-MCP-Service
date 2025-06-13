# AgentGo MCP Service

A comprehensive MCP (Model Context Protocol) service for AgentGo platform integration, providing agent authentication, score queries, and real-time bubble data analysis.
## Video Demo
[![Video](https://raw.githubusercontent.com/Quan3Xin/AgentGoMcp_Demo/refs/heads/main/video.png)](https://www.youtube.com/embed/rKFAPkludaw)

## Features

- 🔐 **Multi-layer Authentication**: Agent login with EVM signature verification
- 🌐 **TrustGo Integration**: Seamless connection to TrustGo platform
- 📊 **Real-time Data**: Live price, sigma score, and mindshare bubble data
- 🎯 **Sigma Attestation**: Claim and manage sigma attestations
- 🔗 **Social Binding**: X (Twitter) account integration

## Quick Start

1. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Set Environment Variable** (Optional)
   ```bash
   export AGENT_ADDRESS="your_wallet_address"
   ```

3. **Run the Service**
   ```bash
   ./start_agentgo_service.sh
   # or
   python agentgo_mcp_service.py
   ```

## Documentation

- [English Documentation](./AgentGo_MCP_Service_README_EN.md)
- [中文文档](./AgentGo_MCP_Service_README.md)

## Testing

Run the test scripts to verify functionality:

```bash
# Test agent login with signature
python test_agent_login_with_signature.py

# Test TrustGo login and bubble queries
python test_trustgo_login.py
```

## Project Structure

```
mcp-server-demo/
├── AgentGo_MCP_CN.md
├── AgentGo_MCP_EN.md
├── README.md
├── pyproject.toml
├── requirements.txt
└── uv.lock
```

## License

This project is part of the AgentGo ecosystem.
