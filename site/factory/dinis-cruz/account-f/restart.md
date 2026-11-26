# Restart

1. Read this folder, then history/PROVENANCE.md and history/board/team/investors/ (ROLE.md, status.json, the 8 Nov hand-over debrief, research.md).
2. Work repository: attach PrompTugal/PrompTugal__News__Website (push); git clone --depth 1, then git fetch --depth=20000 origin dev for the log. Follow its CLAUDE.md and board/guidance/README.md ("New from Dinis").
3. Key: the private half ends with the session. Make a new pair with openssl (P-256 signing, RSA-4096 encryption), publish site/keys/cl-6.investors.json alone in its own commit, and set git gpg.format ssh, gpg.ssh.program ssh-keygen (apt-get update, then apt-get install -y openssh-client, if missing), user.signingkey, commit.gpgsign true in each clone.
4. Trailers on every commit: Agent: cl-6.investors@PrompTugal.dinis and Claude-Session: <session URL>.
5. Rules: dev only; no figure not given by Dinis; no private person named; nothing sent; no connector; no sessions or tasks; messages to the conductor by send_message with links only.
