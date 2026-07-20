# Ferrostar engagement — internal summary
What we built: AI triage layer over sensor alarm logs. Classifies ~1,400 weekly alarms into act-now / monitor / ignore, produces a Monday digest for plant leadership.
Reported outcome (client-stated, not independently measured): maintenance team reviews ~120 alarms/week instead of 1,400.
Custom parts: alarm-code mapping (~3 weeks), digest format (1 week). Reusable parts: triage logic, digest pipeline (~70% of the build).
Retainer economics: $8,500/mo, roughly 15 hrs/mo of our time after setup.
