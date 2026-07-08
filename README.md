# relux-appsflyer

AppsFlyer adapter for
[relux-analytics](https://github.com/relux-works/relux-analytics). Analytics events
declared as Relux actions are delivered to AppsFlyer without vendor code in views or
business logic.

## Installation (Swift Package Manager)

```swift
.package(url: "https://github.com/relux-works/relux-appsflyer.git", from: "1.0.0")
```

```swift
.product(name: "ReluxAppsFlyer", package: "relux-appsflyer")
```

## Usage

Register the adapter alongside ReluxAnalytics in your Relux runtime and configure it
with your AppsFlyer dev key. See
[relux-analytics-sample](https://github.com/relux-works/relux-analytics-sample) for the
module wiring pattern.

<!-- relux-ecosystem:start -->

## About Relux Works

This project is part of the open-source ecosystem of
[Relux Works](https://relux.works), an AI-native software development studio.
We build fixed-price MVPs, rescue vibe-coded apps, run local AI inference, and
train teams to work with coding agents. Much of the infrastructure behind that
work is open source.

- Full catalog: [relux.works/en/open-source](https://relux.works/en/open-source/)
- Agentic enablement: [agent harnesses & team training](https://relux.works/en/agentic-enablement/)
- Hire us the agent-native way: point your assistant at `https://api.relux.works/mcp`
- Contact: ivan@relux.works

<!-- relux-ecosystem:end -->

## License

See [LICENSE](LICENSE).
