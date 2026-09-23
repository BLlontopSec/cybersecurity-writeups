## 1. Summary (Executive Summary)

- **Name of the challenge/machine:** (Ex. _Machine: Legacy en Hack The Box_).
- **Difficult:** (Beginner, Intermediate, Advanced, Expert ).
- **Short Description:** What was the challenge about and what did you achieve? (Ex. _Administrator access was gained by exploiting the MS08-067 vulnerability._).
- **Target IP:** (if applicable).

## 2. Recognition Phase (Reconnaissance / Enumeration)

Here you explain how you discovered the target. Include the exact commands you used.

- **Port scanning:** Show the command of `nmap` and the open ports the you found.
- **Service analysis:** what web pages, data base or services was running in that ports.
- _Tip:_ Put screenshots o terminal text snippets (use code blocks).

## 3. Exploitation Phase (Exploitation / Initial Foothold)

Explain how you managed to access the system for the first time.

- **Identification of the attack vector:** What vulnerability did you find in the listed services? (Ex. a plugin of WordPress outdated, default credentials, etc.).
- **The Attack:** explain what _exploit_ did you use, if you have to modify some script or create the _payload_ (carga útil).
- **Result:** Show the exact time that you obtain your first terminal (`shell`) in the system and read the first flag (Flag de usuario).

## 4. Privilege Escalation

Once inside as a limited user, explain how you became **Root** or **Administrator**.

- **Internal enumeration:** What tools did you use to look for internal weaknesses? (Ex. `linpeas`, `winpeas`, or manual commands).
- **Internal exploitation:** What vulnerability did you exploit (a misconfigured file, a scheduled cron task, a vulnerable kernel)?
- **Total Control:** Screenshot obtaining the total control and the final flag (Flag de root).

## 5. Conclusion and Mitigation (Remediation)

A professional write-up not only tells how you broke the system, but also **how to fix it**.

- Briefly explain what security patches should have been applied or what settings should have been changed to prevent the attack.