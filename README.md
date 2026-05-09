# pj-react-web

Vite + React + TypeScript + Tailwind framework layer for
[`kata`](https://github.com/yukimemi/kata).

Sits above [`yukimemi/pj-pnpm`](https://github.com/yukimemi/pj-pnpm)
(which supplies `package.json` and pnpm scripts) and brings the
Vite/React/Tailwind/Vitest scaffolding plus a minimal `src/`
skeleton suitable for `pnpm dev` to boot a working page right
after `kata init`.

The companion layer for Firebase Hosting + Firestore + Storage +
Vercel is [`yukimemi/pj-firebase`](https://github.com/yukimemi/pj-firebase) —
optional, layered on top.

See [`template.toml`](./template.toml) for the file list and merge
modes, and [`AGENTS.md.react-web`](./AGENTS.md.react-web) for the
layer's agent guidance (which becomes a marker block in the
consuming repo's `AGENTS.md`).

## License

MIT.
