# Sandbox repository for spec v140.1 AC-11

Source of the files in the throwaway repo `brunojdsz/radeas-deploy-center-sandbox` (private). It exists only so
`apps/api/tests/test_deploy_center_sandbox.py` can run the real `GitHubClient` against real GitHub without
touching `Radeas/radeas-analyst-amplifier`. The workflows take the same inputs as the real ones but have **no cloud
credentials and deploy nothing**. Set up with `.claude/scripts/v140_1_sandbox_setup.sh`.
