Small tools that do one thing well. Open source, written in Go, made in Austria.

| [ZaaS](https://github.com/haraig/zaas) | [Spellcast](https://github.com/haraig/spellcast) |
|---|---|
| **Randomness as a Service.** Dice, coins, UUIDs, passwords, words and more, as a free REST API. | **Claude, right where you are typing.** Select text in any Windows app, press CapsLock + 1, and translate, rewrite or explain it in place. |
| [Try it](https://zaas.at) · [API docs](https://zaas.at/docs) | [Read more](https://github.com/haraig/spellcast#readme) |

Roll a d20 right now:

```bash
curl https://zaas.at/api/v1/dice?sides=20
```

**How we build:** Go · MIT license · tested in CI on every change · documented
