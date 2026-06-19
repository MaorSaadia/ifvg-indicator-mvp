# MS iFVG Framework MVP

Original Pine Script v6 indicator inspired by public ICT/SMC concepts:
- Liquidity sweeps from confirmed swing pivots
- Body-based FVG candidates
- IFVG confirmation after recent SSL/BSL sweep
- Clean DD+/DD- line, BE/SL visual aids
- Asia/London session highs/lows using New York time
- 08:30 NY data wick markers
- Checklist panel and alert framework

This is an MVP foundation. It does not copy invite-only code or protected implementation logic from any third-party indicator.

## Suggested Codex tasks
1. Compile and fix Pine syntax issues in `ifvg_framework_mvp.pine` without changing the trading logic.
2. Add HTF PD Array module using `request.security()` with `lookahead_off`.
3. Add SMT divergence module against ES/NQ/YM configurable correlated symbol.
4. Add Series FVG merge mode for adjacent same-direction body gaps.
5. Add active model lifecycle states: Active, Completed at opposing liquidity, Invalidated at SL.
6. Add theme presets: Dodger Blue, Institutional Gray, Gold/Navy, Minimal Monochrome.
