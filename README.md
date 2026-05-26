A based-on [`Backslashxx/KernelSU`](https://github.com/backslashxx/KernelSU)

## Integration
```sh
curl -LSs "https://raw.githubusercontent.com/Sorayukii/KernelSU-Next/stable/kernel/setup.sh" | bash -s hookless
```

## Instruction
- Remove all manual hook implementation
- Disable ``CONFIG_KPROBES``
- Enable ``CONFIG_KSU`` ``CONFIG_KSU_TAMPER_SYSCALL_TABLE`` and ``CONFIG_KSU_EXTRAS``
- Use KSU-next manager CI build [Link](https://t.me/ksunext_ci)