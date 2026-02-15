<section id="learning-with-ai">
  <h2>Learning with AI</h2>

  <h3>Topics to Learn</h3>
  <ul>
    <li>
      <strong>Layer 2, Layer 3, and Layer 4 protocol behavior, limitations, and capabilities</strong>
      <ul>
        <li>Understand what each layer naturally exposes (and what it does not) in real networks.</li>
        <li>Learn how constraints (firewalls, segmentation, filtering, NAT, degraded links) impact visibility and interpretation.</li>
        <li>Identify what conclusions are reasonable versus what must be treated as uncertain or inferred.</li>
      </ul>
    </li>
    <li>
      <strong>Traffic packet structure and protocol breakdown at a low level</strong>
      <ul>
        <li>Review packet structure from headers to payload (e.g., Ethernet/IP/TCP/UDP/ICMP fields).</li>
        <li>Understand what specific flags, codes, and responses can indicate about reachability and network behavior.</li>
        <li>Connect packet-level observations to high-level discovery outcomes and visualization decisions.</li>
      </ul>
    </li>
  </ul>

  <h3>How AI Is Used</h3>
  <ul>
    <li>
      <strong>Breaking down protocol mechanics step-by-step</strong>
      <ul>
        <li>Explain protocol behavior in plain language with clear examples and expected outcomes.</li>
        <li>Clarify why specific responses occur (e.g., timeouts vs. rejects, open vs. filtered states).</li>
      </ul>
    </li>
    <li>
      <strong>Exploring inference limits and edge cases</strong>
      <ul>
        <li>Evaluate scenarios where signals may be misleading (segmentation, rate-limiting, asymmetric paths).</li>
        <li>Stress-test assumptions and identify where uncertainty should be represented in NetTower.</li>
      </ul>
    </li>
    <li>
      <strong>Supporting design decisions for discovery and visualization</strong>
      <ul>
        <li>Compare tradeoffs between different discovery approaches and what they realistically reveal.</li>
        <li>Help decide what information should be surfaced to users versus kept internal.</li>
      </ul>
    </li>
    <li>
      <strong>Validating reasoning about constrained network environments</strong>
      <ul>
        <li>Confirm that conclusions drawn from probe results are technically sound and appropriately cautious.</li>
        <li>Improve accuracy of project write-ups by grounding claims in protocol behavior and constraints.</li>
      </ul>
    </li>
  </ul>

  <p>
    <em>
      The AI component supports technical learning rather than adding AI-based product features.
    </em>
  </p>
</section>
