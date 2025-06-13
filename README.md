# AgentGo MCP Service

A comprehensive MCP (Model Context Protocol) service for AgentGo platform integration, providing agent authentication, score queries, and real-time bubble data analysis.

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

- [English Documentation](./AgentGo_MCP_EN.md)
- [中文文档](./AgentGo_MCP_CN.md)

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
## Project Structure

mcp-server-demo/
├── agentgo_mcp_service.py      # Main service file
├── agentgo_api_test.py         # API testing utilities
├── requirements.txt            # Python dependencies
├── start_agentgo_service.sh    # Startup script
├── test_*.py                   # Test scripts
└── backup/                     # Archived files
```

## License

This project is part of the AgentGo ecosystem.