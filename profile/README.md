<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/OpenCourant/branding/main/logo-dark.svg">
  <img alt="OpenCourant" src="https://raw.githubusercontent.com/OpenCourant/branding/main/logo.svg" width="420">
</picture>

### The community continuation of OpenRadioss

An open-source explicit finite element solver for simulating crashes, impacts,
explosions, and other highly nonlinear dynamic events. Free software under the
GNU AGPL v3.

**[Website](https://opencourant.org)** ·
**[Downloads](https://opencourant.org/downloads/)** ·
**[Forum](https://github.com/orgs/OpenCourant/discussions)** ·
**[Chat](https://chat.rockylinux.org/rocky-linux/channels/opencourant)** ·
**[Email](mailto:hello@opencourant.org)**

---

## What happened

On October 1, 2026, Siemens discontinued the OpenRadioss project. The website
was retired and the GitHub repository was removed without an archive, taking
with it four years of community work on the open-source version of the Radioss
finite element solver.

The code was released under the GNU AGPL v3, and free software doesn't
disappear just because a repository does. OpenCourant continues from the last
available open-source code base, with the full commit history intact, so the
work of everyone who contributed to OpenRadioss is preserved and attributed.

## Get the solver

Pre-built packages are published automatically from continuous integration,
gated on the regression suite:

### **[opencourant.org/downloads](https://opencourant.org/downloads/)**

That page always reflects the platforms currently being produced. To build from
source, start with
[HOWTO.md](https://github.com/OpenCourant/OpenCourant/blob/main/HOWTO.md).

## Where to talk

| | |
| --- | --- |
| **[Forum](https://github.com/orgs/OpenCourant/discussions)** | GitHub Discussions, for questions, proposals, release threads and announcements. Start here. |
| **[Chat](https://chat.rockylinux.org/rocky-linux/channels/opencourant)** | Realtime, in `#opencourant` on the Rocky Linux Mattermost. |
| **Issues** | Bug reports and tracked work, in the relevant repository. |
| **[Email](mailto:hello@opencourant.org)** | hello@opencourant.org, for anything that doesn't fit the above. |

## Repositories

| | |
| --- | --- |
| [**OpenCourant**](https://github.com/OpenCourant/OpenCourant) | The solver: Starter, Engine, and the input reader. |
| [**Tools**](https://github.com/OpenCourant/Tools) | Converters, the launcher GUI, and the SDK. |
| [**extlib**](https://github.com/OpenCourant/extlib) | External build libraries, with recovery provenance documented. |
| [**ci-images**](https://github.com/OpenCourant/ci-images) | CI container images, published to `ghcr.io/opencourant`. |
| [**opencourant.org**](https://github.com/OpenCourant/opencourant.org) | The website. |
| [**branding**](https://github.com/OpenCourant/branding) | Logos and marks, CC BY-SA 4.0. |

## How to help

- **Check your downloads folder.** A build dependency that was never kept in
  git disappeared with the upstream repository, and we are still recovering it.
  Donated copies from the community have already improved the Linux builds and
  unblocked arm64.
  [See the callout →](https://github.com/orgs/OpenCourant/discussions/10)
- **The open reader.** The AGPL-licensed input reader already in the repository
  is a handful of functions short of replacing the proprietary one on every
  platform, ARM included. It is the durable fix for an entire class of problem.
- **Testing on real models.** The regression suite gates every release, but it
  cannot cover the range of decks people actually run. Try your own models and
  tell us what breaks.
- **Former OpenRadioss maintainers and community leaders**, please get in
  touch. We want this project's technical direction and governance to be set by
  the people who built it.

---

Radioss is a trademark of its respective owner. OpenCourant is an independent
community project and is not affiliated with or endorsed by Siemens or Altair.
