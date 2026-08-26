# railnode

Release artifacts for the AgentRail node. **No source here** — this repository holds
published binaries only, so a machine running the installer needs no credential of ours.

Install through the control plane you are enrolling into, which serves the script:

    curl -fsSL https://your-control-plane/v1/nodes/install.sh \
      | sh -s -- --token <ticket> --url https://your-control-plane

The ticket is one-time; create it in the console under Nodes -> Add node.
