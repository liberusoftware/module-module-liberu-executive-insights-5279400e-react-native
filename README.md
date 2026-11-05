# Liberu Executive Insights · React Native · Expo

Independent presentation module skeleton for **Liberu Executive Insights**. Intended boundary: native ios/android application using react native and expo.

**Status: skeleton.** This repository supplies package/build structure and an explicit extension entry. It is not a completed feature, production API integration or registry publication. Existing implementations and package identities remain authoritative.

**Identity review required:** documentation records multiple source identities or a naming conflict for this capability. This skeleton keeps the exact source/plan key below distinct; it does not establish equivalence, a stable package contract or safe replacement of an existing implementation.

- Capability/source key: `liberusoftware/module-liberu-executive-insights`.
- Presentation scope: [Liberu Executive Insights](https://github.com/liberusoftware/documentation/blob/main/projects/accounting/react-native/liberu-executive-insights.md).
- Canonical ownership record: [source/plan group](https://github.com/liberusoftware/documentation/blob/main/projects/accounting/nextjs/liberu-executive-insights.md).
- Registry identity: `@liberusoftware/module-module-liberu-executive-insights-5279400e-react-native`.
- Foundation: [module-boilerplate-react-native](https://github.com/liberusoftware/module-boilerplate-react-native) at `b63bc1b11fe769e2e547a3f1fced6116556fe9e1`.

## Develop and verify

```bash
npm ci
npm run typecheck
npm run build
npm pack --dry-run
```

The public npm export currently provides `moduleDefinition`, explicit registration metadata. No UI screens or API calls are implemented. Add capability UI and injected contract mapping through deliberate exports.

Use the committed locks and declared toolchain. Read [AGENTS.md](AGENTS.md) and the [presentation runbook](https://github.com/liberusoftware/documentation/blob/main/guides/presentation/REACT-NATIVE.md). Keep host routing, navigation, session integration and deployment outside reusable capability code. Keep Laravel policy, tenant context, validation, transactions, persistence and state transitions in the canonical owner. Do not infer endpoints or business DTOs from this registration descriptor.

Implement reviewed loading, empty, denied, invalid, stale/conflict, pending and recoverable failure states when adding real workflows. Test meaningful allowed/denied/wrong-tenant behavior against the authoritative API or public action. Reconcile uncertain writes before retrying and clear scoped cached data on logout. For device targets, review lifecycle, secure storage and platform support; a local draft is not a completed server transaction.

## Documented consumer project families

These project skeletons belong to documented consumer scopes. Their presence does not prove integration or feature parity; review compatible core/API contracts before enabling this package.

- [Accounting ERP](https://github.com/liberusoftware/project-accounting-erp-mobile-react): Ledgers, tax, reporting and finance workflows.
- [Billing](https://github.com/liberusoftware/project-billing-mobile-react): Subscriptions, pricing, payments and provisioning.
- [Genealogy](https://github.com/liberusoftware/project-genealogy-mobile-react): Family trees, research, evidence and collaboration.

## Other presentations of this capability

The companion repositories use the same canonical scope and preserve their own presentation lifecycle. Availability is recorded by the repository inventory; a repository link is not evidence of an implemented feature.

- [Laravel · Filament](https://github.com/liberusoftware/module-module-liberu-executive-insights-5279400e-filament).
- [Laravel · Inertia · Vue](https://github.com/liberusoftware/module-module-liberu-executive-insights-5279400e-vue-inertia).
- [Laravel · Inertia · React](https://github.com/liberusoftware/module-module-liberu-executive-insights-5279400e-react-inertia).
- [Nuxt · Vue](https://github.com/liberusoftware/module-module-liberu-executive-insights-5279400e-nuxt).
- [Next.js · React](https://github.com/liberusoftware/module-module-liberu-executive-insights-5279400e-nextjs).
- [Flutter · Mobile](https://github.com/liberusoftware/module-module-liberu-executive-insights-5279400e-flutter).
- [Dart · Desktop](https://github.com/liberusoftware/module-module-liberu-executive-insights-5279400e-dart-desktop).
- [Dart · Mobile](https://github.com/liberusoftware/module-module-liberu-executive-insights-5279400e-dart-mobile).

## Release boundary

Build and inspect a packed artifact in a clean consumer before an authorized registry release. Keep prerelease/skeleton status until implemented behavior and supported runtimes are verified. Repository creation does not publish to Packagist, npm or pub.dev. Native signing and store distribution are separate application responsibilities.
