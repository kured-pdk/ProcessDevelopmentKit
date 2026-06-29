# Quickstart

This quickstart explains how to use the repo to get started with documentation checks and installing a sample PDK locally.

Prerequisites
- git
- Python 3.10+
- pip

Steps
1. Clone the repo
   git clone https://github.com/kured-pdk/ProcessDevelopmentKit.git
2. Create and switch to the branch (if you didn't use the web UI branch creation)
   git checkout -b pdk-starter
3. Install docs link checker (optional)
   pip install markdown-link-check
4. Run quick checks
   markdown-link-check PDK_RESOURCES.md

Note: Full EDA flows (OpenROAD, mflowgen) require Docker or native installs and are not executed in this quickstart.

Optional: Run CI locally (basic)
- You can run link checks locally with the installed tool above. For more advanced workflow testing, use a container or CI runner with the OpenROAD/mflowgen toolchain.
