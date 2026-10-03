# Christopher P. Hurley

Roseville, CA · Email: [cphurley82@gmail.com](mailto:cphurley82@gmail.com) · LinkedIn: [linkedin.com/in/cphurley82](https://www.linkedin.com/in/cphurley82)

## Summary

Senior staff engineer who leads system-level software efforts: virtual platforms, hardware models, and the test and CI systems firmware teams rely on to build and debug. Sets technical direction (test strategy, code quality, review practice), grows teams through hiring and mentoring, and delivers hands-on in C++ and SystemC.

## Skills

- Leadership: technical strategy, mentoring, hiring, code review policy, cross-team coordination
- Languages: C++, C, Python, SystemVerilog, Verilog, JavaScript, Ruby
- Modeling: SystemC (TLM-2.0), virtual platforms, Arm and RISC-V simulation, UVM, RTL/DPI integration
- Firmware: Trusted Firmware-A (TF-A), UEFI, Zephyr, SSD/NAND firmware and media, hardware bring-up
- Tools: CMake, Conan, GoogleTest, pytest, pybind11, clang-format, clang-tidy, Git, Docker, Linux
- Practices: test-driven development, CI/CD, open-source upstreaming, AI-assisted development, Scrum

## Experience

### Qualcomm — Senior Staff Engineer (2025-04 – Present; Remote)

- Defined the test strategy for a data center SoC virtual platform, from unit tests to full boot chain, built team alignment around it, and led its rollout into the main build and CI.
- Drove a processor-subsystem model from first code to booting real firmware, establishing the virtual platform as a primary development and regression platform for multiple firmware teams.
- Raised the team's engineering practices: wrote the code review policy and code-ownership guidance, and phased lint, static-analysis, and formatting gates into CI.
- Grew the team: built the coding interview and scoring rubric used in hiring, interviewed candidates, onboarded several new engineers, and kept regular 1:1s with teammates.
- Supported firmware customers with development releases, demos, and guides; traced reported failures across model, firmware, debugger, and hardware data, fixing each defect family with regression tests.
- Developed a Python interface to the virtual platform (pybind11, pytest), first for test automation, then expanded into a customer-facing tool for firmware teams.
- Modeled inter-processor mailboxes, timers, interrupt controllers, and clock and power control with unit and firmware-level tests; extended TF-A-to-UEFI boot support across multiple SoC platforms.
- Replaced an internal fork with upstream DBT-RISE-RISCV (open-source RISC-V simulator), cutting its CI time from about 1.5 hours to 15 minutes; upstreamed fixes to DBT-RISE and SystemC-Components (SCC).
- Brought up a full SoC virtual platform in CI with a documented workflow for adding new platforms; built the SystemC unit test framework (GoogleTest, CMake) and a router-based TLM-2.0 address decoder.
- Organized the team's technical sync and in-person planning; introduced AI-assisted development tooling and documented the setup for the team.

### Solidigm — Software Engineer (2021-07 – 2025-03; Remote)

- Owned the NAND media model for firmware development and pre-silicon SoC verification; onboarded two teams to it and set up source mirroring across three repositories with IT and legal.
- Aligned and extended NAND media models to work with partner stacks, shaping a unified strategy.
- Ran the weekly power-on sync for a new program and drafted its requirements and development plan.
- Designed and deployed simulation-driven CI for firmware and modernized the simulation toolchain (Clang 17, reproducible builds), catching regressions early.
- Stood up firmware infrastructure, CI, and first builds for a QLC program and powered on the first drives, unblocking wider team development; repeated bring-up across multiple programs and form factors.
- Integrated SoC and NAND models for shift-left development, enabling an ahead-of-schedule functional demo on a new SoC/NAND combination.
- Implemented and optimized a QLC-focused garbage-collection algorithm with DRAM caching, improving I/O stability and performance.

### Intel — Software Engineer (2017-03 – 2021-06; Folsom, CA)

- Led team planning, Scrum processes, and DevOps initiatives; mentored new engineers and performed code reviews to improve quality and velocity.
- Built C++ models for 3D XPoint and NAND (TLM-2.0, SystemC/SystemVerilog interfaces), including a unified NAND model core reused across RTL validation, emulation, virtual platforms, and QoS models.
- Collaborated with architecture and design teams to model new NAND features, enabling earlier firmware development and pre-silicon feedback.
- Replaced manual timing spreadsheets with versioned Python tooling for rapid what-if analysis.
- Architected a high-performance, multithreaded C++/SV-DPI testbench for transactor validation.

### Oracle — Cloud Application Developer (2016-07 – 2017-03; Rocklin, CA)

- Led a licensing product selection tool from requirements gathering through UAT and go-live.
- Migrated an internal sales configuration system to Oracle CPQ Cloud: front end (JavaScript/HTML), back end (BML/SQL), and Python test automation.
- Introduced Jira and authored process documentation and functional specifications.

### Intel — Software Engineer (2014-04 – 2016-07; Folsom, CA)

- Drove adoption of Scrum with regular releases; ran stand-ups, sprint planning, and customer syncs.
- Architected a SystemC/Python component testbench for high-level testing via customer-facing interfaces, reducing test times from minutes to seconds.
- Consolidated builds into one cross-platform CMake configuration with automated testing and packaging, cutting build times from ~5 minutes to ~30 seconds; added millisecond GoogleTest unit tests.
- Unified multiple disparate models into one configurable core with role-specific interfaces, coordinating parameters with design and architecture.

### Intel — System Test Engineer (2009-09 – 2014-03; Folsom, CA)

- Led joint development with tester vendors on new products and drive interfaces, increasing code reuse and collaboration across product lines.
- Developed C++ manufacturing test flows for SAS, Fibre Channel, and PCIe SSDs from initial development through high-volume manufacturing.
- Moved test infrastructure from a limited Windows PC setup to a custom, highly parallel Linux system.
- Established Jira and Confluence for the team; partnered with firmware teams to debug manufacturing issues and reduce test costs.

### Additional Experience

- Intel — Design Engineering Intern (2008-06 – 2009-08): Assisted with RTL design, synthesis, verification, and timing. Developed and taught a SystemVerilog curriculum for engineers.
- UC Davis — Micromouse Robotics Team Lead (2008-09 – 2009-06): Led a 5-person team to design, build, and program an autonomous maze-solving robot, winning the 2009 UC Davis Micromouse competition.
- Cub Scouts — Assistant Cubmaster and Den Leader (2023 – Present): Volunteer; help lead the pack and run den meetings.

## Education

B.S., Computer Engineering — University of California, Davis (2009)
