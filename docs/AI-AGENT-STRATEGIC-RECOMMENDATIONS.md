# AI Agent Strategic Recommendations

This repository should remain a **specialist PIPTICK TradingView connector**, not the entire trading platform.

Keep the connector narrow, reliable and provider-specific. Evaluate authentication, rate limits, failure modes, runtime assumptions, licensing and observability before expanding it.

PIPTICK should own provider-neutral concepts such as instruments, time series, indicators, strategies, signals, orders, positions and risk. Expose a clean adapter boundary so PIPTICK can replace or add providers later.

Do not add unrelated finance-terminal features here simply because they are popular elsewhere. Put core-domain capabilities in PIPTICK and keep this repo focused on TradingView integration.