# Health Checks

Health checks answer whether a service is usable.

Types:

- Liveness: is the process alive?
- Readiness: can it receive traffic?
- Startup: has it finished booting?

Good health checks verify:

- App process
- Database connection if required
- Critical dependency status
- Response time

Avoid:

- Expensive checks
- Checks that overload dependencies
- Always returning success

