# Miso Robotics

Miso Robotics is a Pasadena, California kitchen-automation company that builds AI-powered
robotics and restaurant operations software for commercial food service. Its flagship
product, **Flippy**, is an autonomous fry station that uses computer vision and
NVIDIA-accelerated motion planning to identify food items, detect doneness and run up to
100 baskets per hour on existing commercial fryers (Frymaster, Henny Penny, Pitco). Miso
also ships **Zippy**, built on the acquired **Zignyl** platform — a real-time digital shift
manager for forecasting, scheduling, task management, incentives and payroll that connects
to restaurant point-of-sale systems.

## API surface

**No public developer API.** As of 2026-08-01 the enrichment pipeline found no
OpenAPI/Swagger contract, no GraphQL endpoint, no AsyncAPI or webhook catalog, no MCP
server, no A2A agent card, no SDKs in any public package registry, and no developer
portal, documentation site or API reference. Point-of-sale integrations (Toast, PAR and
others, inherited with the Zignyl acquisition) are private partner connections arranged
through sales rather than a self-serve public API.

Hosts probed: `misorobotics.com`, `www.misorobotics.com`, `info.misorobotics.com`,
`invest.misorobotics.com`, `zignyl.com`, `app.zignyl.com`, plus non-resolving
`api.` / `app.` / `docs.` / `developer.misorobotics.com` and `api.zignyl.com`.
Full results in `well-known/miso-robotics-well-known.yml`.

The public GitHub organization [MisoRobotics](https://github.com/MisoRobotics) carries 120
repositories, predominantly forks of ROS/robotics (MoveIt2, rosbridge_suite, librealsense,
apriltag_ros) and cloud-infrastructure projects (Terraform modules, Google Cloud Build
tooling). None is a client SDK for a Miso API.

> Note: the `@miso.ai/*` npm packages and `docs.miso.ai` belong to **Miso Technologies**
> (search/recommendation AI), a different company — they are not Miso Robotics artifacts.

## Artifacts

- `security/miso-robotics-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC
- `well-known/miso-robotics-well-known.yml` — probed `/.well-known/` + spec-path discovery (all negative)
- `llms/miso-robotics-llms.txt` — generated llms.txt

## Links

- Website — https://www.misorobotics.com/
- Products — https://www.misorobotics.com/products
- Blog — https://www.misorobotics.com/blogs (RSS: https://misorobotics.com/rss.xml)
- Support & FAQs — https://www.misorobotics.com/support-faqs
- Newsroom — https://www.misorobotics.com/newsroom-press-media-kit
- GitHub — https://github.com/MisoRobotics
- Secondary market — https://forgeglobal.com/miso-robotics_stock/
