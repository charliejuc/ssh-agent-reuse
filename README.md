# SSH AGENT REUSE

Script that allows the **ssh-agent** to be reused between terminals.

You only need to run it inside **.bashrc, .zshrc or similar file** as follow.

```bash
eval `/your_path/ssh-agent-reuse/ssh-agent-reuse.sh` &> /dev/null
```

Remember to give **permissions to run**.

```bash
chmod +x /your_path/ssh-agent-reuse/ssh-agent-reuse.sh
```

Tested in Debian Strecth.