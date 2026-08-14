# ECZ-ID MCP Readiness

## Move from "it works in the demo" to evidence your reviewers can assess.

A practical MCP readiness resource for teams preparing MCP servers and integrations for production, security review or procurement.

### Start free

[Run the free MCP Readiness Scanner](https://mcp.ecocitizenz.com/scanner?utm_source=github&utm_medium=repository&utm_campaign=mcp-readiness&utm_content=scanner)

[Install ECZ-ID MCP Trust Free](https://marketplace.visualstudio.com/items?itemName=ecocitizenz.eczid-mcp-trust)

[Install the free MCP & Agent Check GitHub App](https://github.com/marketplace/ecz-id-mcp-agent-check)

[Download the free MCP & AI Agent Trust Preflight](https://developers.ecocitizenz.com/downloads/eczid-mcp-agent-trust-preflight.pdf?utm_source=github&utm_medium=repository&utm_campaign=mcp-readiness&utm_content=preflight)

[Explore professional MCP services](https://mcp.ecocitizenz.com?utm_source=github&utm_medium=repository&utm_campaign=mcp-readiness&utm_content=services)

---

## MCP production-readiness checklist

Before relying on an MCP implementation, review:

### 1. Configuration

- Does the configuration parse correctly?
- Is the intended transport explicit?
- Are package/container versions pinned where appropriate?

### 2. Tool surface

- Which tools are exposed?
- Which inputs can trigger destructive or external actions?
- Are tool schemas stable and reviewable?

### 3. Credentials

- Are secrets embedded directly in configuration?
- Are credential-shaped environment references broader than required?
- Can access be reduced?

### 4. Authorization

- Who or what can invoke each capability?
- Are shared static credentials standing in for per-user or per-agent authority?
- Are scopes and boundaries explicit?

### 5. Change

- What baseline exists?
- Can package, endpoint, tool or schema drift be detected?
- What is the rollback path?

### 6. Transport and deployment

- Is the implementation session-bound or suitable for the intended deployment model?
- Does it behave correctly under reconnect/restart conditions?
- Are production assumptions written down?

### 7. Evidence

- Can reviewers reproduce the test conditions?
- Can operator identity or published proof be independently re-checked?
- Are limitations recorded rather than hidden?

---

## Free scanner

The ECZ-ID MCP Readiness Scanner performs passive configuration analysis in the browser and does not execute the MCP configuration.

[Run the free scanner](https://mcp.ecocitizenz.com/scanner?utm_source=github&utm_medium=repository&utm_campaign=mcp-readiness&utm_content=run-scanner)

---

## Developer tooling

For ongoing local inspection:

[ECZ-ID MCP Trust](https://developers.ecocitizenz.com/mcp-trust?utm_source=github&utm_medium=repository&utm_campaign=mcp-readiness&utm_content=mcp-trust)

For pull-request and committed-configuration checks:

[ECZ-ID MCP & Agent Check](https://github.com/marketplace/ecz-id-mcp-agent-check)

---

## Professional MCP Readiness Audit

For teams that need a human-reviewed assessment rather than only self-service tooling, EcoCitizenz currently offers the fixed-scope **MCP Readiness Audit at £395**.

It assesses one MCP implementation and produces a severity-ranked findings report and remediation plan.

[See the £395 MCP Readiness Audit](https://mcp.ecocitizenz.com?utm_source=github&utm_medium=repository&utm_campaign=mcp-readiness&utm_content=audit)

---

## Public operator proof

**ECZ-ID VERIFIED - ECZ-GB-RBS1NW**

[View current public identity and evidence](https://resolver.ecocitizenz.org/passport/ECZ-GB-RBS1NW)

Review findings and Resolver evidence within your own security and procurement policy.