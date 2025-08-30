---
layout: page
permalink: /Projects/index.html
title: Projects
---


_Last updated: Aug 30, 2025_

# Selected Projects

<div class="projects">

  <!-- Project 4 -->
  <article class="card" id="sync-inverters">
    <div class="third">
      <img src="/images/Large.png" alt="Synchronization of large-scale inverters" loading="lazy">
    </div>
    <h3>Synchronization for Renewable-Energy–Based Inverters</h3>
    <div class="meta">2025– · Large-scale synchronization &amp; power sharing of inverters</div>
    <div class="tags">
      <span class="tag">Nonlinear theory</span>
      <span class="tag">GFM / GCFI</span>
      <span class="tag">Synchronization</span>
      <span class="tag">Power sharing</span>
    </div>
    <p>
      We design unified droop/VOC/SMC behaviors under a single contraction metric. The method yields
      <em>exponential</em> convergence of phases and voltages, proportional power sharing without a slack bus,
      and fast non-oscillatory current limiting during faults or large disturbances—robust to parameter spread
      and changing network R/X and SCR.
    </p>
    <ul class="list">
      <li><strong>Focus:</strong> metric synthesis, DC–AC coupled modeling, distributed sharing laws</li>
      <li><strong>Outcomes:</strong> provable sync &amp; RoA bounds; ride-through with bounded THD; topology robustness</li>
      <li><strong>Tools:</strong> MATLAB/Simulink, PLECS/EMT, Python (CVX/YALMIP)</li>
    </ul>
  </article>

  <!-- Project 3 -->
  <article class="card" id="bidirectional-isolated-dcdc">
    <div class="third">
      <img src="/images/two.png" alt="Bidirectional isolated DC-DC 450 V to 3 V hardware" loading="lazy">
    </div>
    <h3>450 V ↔ 3 V Bidirectional Isolated DC-DC</h3>
    <div class="meta">2024–2025 · The 4th Sungrow University Innovation Contest</div>
    <div class="tags">
      <span class="tag">2.5–3.65 V low side</span>
      <span class="tag">430–530 V high side</span>
      <span class="tag">550 W full-load</span>
      <span class="tag">Non-resistive load validation</span>
    </div>
    <p>
      Developed a high-ratio, bidirectional isolated converter with precise voltage regulation and efficient
      power-flow control for charge/discharge. Thermal design and layout were co-optimized across wide input ranges.
    </p>
    <ul class="list">
      <li><strong>Focus:</strong> modulation &amp; current control, magnetics selection, thermal constraints</li>
      <li><strong>Outcomes:</strong> 550 W at full-load; robust operation with dynamic loads</li>
      <li><strong>Tools:</strong> MATLAB/Simulink, PLECS, Altium Designer, FloTHERM XT</li>
    </ul>
  </article>

  <!-- Project 2 -->
  <article class="card" id="ultra-high-efficiency">
    <div class="third">
      <img src="/images/One.png" alt="Ultra-High-Efficiency grid-connected converter prototype" loading="lazy">
    </div>
    <h3>Ultra-High-Efficiency Grid-Connected Power Conversion</h3>
    <div class="meta">2023–2024 · Module-integrated converter</div>
    <div class="tags">
      <span class="tag">Full-bridge (primary)</span>
      <span class="tag">Cycloconverter (secondary)</span>
      <span class="tag">Independent C<sub>dc</sub> control</span>
      <span class="tag">Soft-switching (all devices)</span>
      <span class="tag">Four-quadrant operation</span>
    </div>
    <p>
      Designed and validated a high-efficiency AC interface (primary full-bridge + secondary cycloconverter),
      enabling decoupled capacitor-voltage regulation, low switching loss, and seamless P/Q flow in all four quadrants.
    </p>
    <ul class="list">
      <li><strong>Focus:</strong> topology, control strategy, loss breakdown, EMT verification</li>
      <li><strong>Outcomes:</strong> stable grid tie under weak SCR; reduced device stress with soft-switching</li>
      <li><strong>Tools:</strong> MATLAB/Simulink, LTspice, Altium Designer</li>
    </ul>
  </article>

  <!-- Project 1 -->
  <article class="card" id="multi-agent-platform">
    <div class="third">
      <img src="/images/wheel.png" alt="Two-wheel self-balancing multi-agent platform" loading="lazy">
    </div>
    <h3>Cooperative Multi-Agent Motion Platform</h3>
    <div class="meta">2022 · Outstanding Undergraduate Thesis</div>
    <div class="tags">
      <span class="tag">Self-balancing robot</span>
      <span class="tag">PID scheduling</span>
      <span class="tag">Sliding-mode</span>
      <span class="tag">Adaptive control</span>
      <span class="tag">CANopen</span>
    </div>
    <p>
      Built a two-wheel self-balancing robot for cooperative motion experiments; implemented classical and nonlinear
      controllers and a Raspberry Pi–Simulink toolchain with CANopen actuation.
    </p>
    <ul class="list">
      <li><strong>Focus:</strong> platform design, controller comparison, multi-agent coordination</li>
      <li><strong>Stack:</strong> FAULHABER, Simulink, CANopen, Raspberry Pi 3B</li>
    </ul>
  </article>

</div>

## Get in touch
If you’re interested in collaborating or would like to see more—such as datasets or EMT models—please get in touch.  
I’m also looking for a postdoctoral position. Email: <strong>qianxi [at] hust.edu.cn</strong>
