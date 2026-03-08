# Commands

This page explains the available commands in EasyTeamShuffle.

EasyTeamShuffle creates teams using members currently connected to a voice channel.

---

# Team Commands

## Split by Team Size

Create teams by specifying the number of players per team.

### Japanese

```
/人数分け <人数>
```

Example

```
/人数分け 3
```

This will split players into teams of **3 members per team**.

---

### English

```
/team_size <players>
```

Example

```
/team_size 3
```

This will create teams with **3 players per team**.

---

## Split by Number of Teams

Create teams by specifying the number of teams.

### Japanese

```
/チーム数分け <チーム数>
```

Example

```
/チーム数分け 2
```

This will split players into **2 teams**.

---

### English

```
/team_count <teams>
```

Example

```
/team_count 2
```

This will divide players into **2 teams**.

---

# Re-shuffle

After teams are created, a **Re-shuffle button** appears under the result message.

Pressing this button will reshuffle the teams using the same settings.

To prevent spam, reshuffling has a **10-second cooldown**.

The result message will also show **which user triggered the reshuffle**.

---

# Requirements

To use EasyTeamShuffle commands:

* You must be connected to a **voice channel**
* The voice channel must have **at least 3 members**
* The bot must have permission to **send messages and embeds**
