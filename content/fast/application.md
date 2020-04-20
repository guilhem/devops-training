+++
weight = 60
+++

# Impact on my application

---

## Github flow

Branch → Pull Request → Validation → Merge

---

{{% section %}}

## 12 factors

1. Codebase
   One codebase tracked in revision control, many deploys
2. Dependencies
   Explicitly declare and isolate dependencies
3. Config
   Store config in the environment
4. Backing services
   Treat backing services as attached resources

---

5. Build, release, run
   Strictly separate build and run stages
6. Processes
   Execute the app as one or more stateless processes
7. Port binding
   Export services via port binding
8. Concurrency
   Scale out via the process model

---

9. Disposability
   Maximize robustness with fast startup and graceful shutdown
10. Dev/prod parity
    Keep development, staging, and production as similar as possible
11. Logs
    Treat logs as event streams
12. Admin processes
    Run admin/management tasks as one-off processes

{{% /section %}}
