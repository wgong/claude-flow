(base) papagame@papa-game:~/projects/wgong/claude-flow$ npx claude-flow@alpha --help

🌊 Claude-Flow v2.0.0-alpha.84 - Enterprise-Grade AI Agent Orchestration Platform

🎯 ENTERPRISE FEATURES: Complete ruv-swarm integration with 90+ MCP tools, neural networking, and production-ready infrastructure
🐝 NEW: Claude Code 1.0.51+ full compatibility with enhanced hooks and batch processing
⚡ ALPHA 84: Enhanced swarm --claude flag for direct Claude Code CLI integration

USAGE:
  npx claude-flow@alpha <command> [options]    # Run latest alpha version
  npx claude-flow@alpha <command> --help       # Get detailed help for any command
  npx claude-flow@alpha --help                 # Show this help
  
  # After local install:
  claude-flow <command> [options]
  claude-flow <command> --help    # Get detailed help for any command

🚀 QUICK START:
  # First time setup (creates CLAUDE.md & .claude/commands)
  npx claude-flow@alpha init
  
  # 🐝 HIVE MIND QUICK START (NEW!):
  claude-flow hive-mind wizard          # Interactive setup wizard
  claude-flow hive-mind spawn "objective"  # Create intelligent swarm
  claude-flow hive-mind spawn "Build API" --claude  # Open Claude Code CLI
  
  # After setup, use without npx:
  claude-flow start --ui --swarm         # Start with swarm intelligence UI
  claude-flow swarm "build REST API"     # Deploy multi-agent workflow
  claude-flow swarm "create service" --claude  # Open Claude Code CLI with swarm

🐝 HIVE MIND COMMANDS (NEW!):
  hive-mind wizard         🎯 Interactive setup wizard (RECOMMENDED)
  hive-mind init           Initialize Hive Mind system with SQLite
  hive-mind spawn <task>   Create intelligent swarm with objective
  hive-mind status         View active swarms and performance metrics
  hive-mind metrics        Advanced performance analytics

📋 CORE COMMANDS:
  init                     Initialize Claude Flow v2.0.0 (creates CLAUDE.md & .claude/commands)
                          --monitoring enables token usage tracking
  start [--ui] [--swarm]   Start orchestration system
  swarm <objective>        Multi-agent swarm coordination
  agent <action>           Agent management (spawn, list, terminate)
  sparc <mode>             SPARC development modes (17 available)
  memory <action>          Persistent memory operations
  github <mode>            GitHub workflow automation (6 modes)
  status                   System status and health
  
📋 SWARM INTELLIGENCE COMMANDS:
  training <command>       Neural pattern learning & model updates (3 commands)
  coordination <command>   Swarm & agent orchestration (3 commands)
  analysis <command>       Performance & token usage analytics (real tracking!)
  automation <command>     Intelligent agent & workflow management (3 commands)
  hooks <command>          Lifecycle event management (5 commands)
  migrate-hooks            Migrate settings.json to Claude Code 1.0.51+ format
  monitoring <command>     Real-time system monitoring (3 commands)
  optimization <command>   Performance & topology optimization (3 commands)
  
📋 ADDITIONAL COMMANDS:
  task <action>            Task and workflow management
  config <action>          System configuration
  mcp <action>             MCP server management
  batch <action>           Batch operations

🔍 GET HELP:
  npx claude-flow@alpha --help                Show this help
  npx claude-flow@alpha <command> --help      Detailed command help

🎯 RECOMMENDED FOR NEW USERS:
  npx claude-flow@alpha hive-mind wizard     # Start here! Interactive guided setup
  npx claude-flow@alpha init                 # Initialize Claude Flow
  npx claude-flow@alpha help hive-mind       # Learn about Hive Mind features
  npx claude-flow@alpha swarm "Build API" --claude  # Quick start with Claude Code CLI

📚 Documentation: https://github.com/ruvnet/claude-flow
🐝 Hive Mind Guide: https://github.com/ruvnet/claude-flow/tree/main/docs/hive-mind
🐝 ruv-swarm: https://github.com/ruvnet/ruv-FANN/tree/main/ruv-swarm
💬 Discord Community: https://discord.agentics.org

💖 Created by rUv with love: https://github.com/ruvnet
