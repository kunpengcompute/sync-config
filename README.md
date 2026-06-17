# sync-config

Kunpeng+BoostKit community mirror sync configuration — powered by [community-mirror](https://github.com/huanglei0308/community-mirror).

This repository runs an automated daily workflow that mirrors repos from:
- **gitcode/kunpengcompute** → **github/kunpengcompute**
- **gitcode/BoostKit** → **github/kunpengcompute**

<!-- SYNC_STATUS_START -->
**Last updated:** 2026-06-17T07:26:21Z
**Flow:** `gitcode/kunpengcompute+BoostKit` → `github/kunpengcompute`
**Status:** ⚠️ **4 repo(s) failed**

| Total | ✅ Synced | ❌ Failed | ⏭️ Skipped |
| ---: | ---: | ---: | ---: |
| 140 | 136 | 4 | 0 |

### 📊 Failure Summary

| Category | Count |
|----------|------:|
| 📤 Push Rejected | 3 |
| 🔒 Pre-receive Hook Declined | 1 |

### ❌ Failed Repos

- **`boostkit-bigdata`** — Rejected by destination server pre-receive hook<br>🔍 Source: API returned HTTP 400<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`anolis-cloud-kernel`** — remote: fatal: pack exceeds maximum allowed size (2.00 GiB)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`velinux-kernel-dev`** — remote: fatal: pack exceeds maximum allowed size (2.00 GiB)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`velinux-kernel`** — remote: fatal: pack exceeds maximum allowed size (2.00 GiB)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

[🔍 View workflow logs](https://github.com/kunpengcompute/sync-config/actions)

<details>
<summary><b>✅ Synced Repos (136)</b></summary>

- `virt-efficiency`
- `CubeSandbox`
- `kacc_crypto`
- `OpenViking`
- `Ultrascan`
- `LowLatencyLib`
- `daft`
- `OmniSkill`
- `diskann`
- `OmniCatalyst`
- `spring-framework`
- `tomcat`
- `simdjson`
- `rapidjson`
- `fbthrift`
- `brpc`
- `kadd-open`
- `pandas`
- `numpy`
- `malloc-bench`
- `skills`
- `boostida`
- `pvm`
- `mysql-server`
- `ceph`
- `suricata`
- `tensorrt-llm`
- `OmniAdaptor`
- `flash-engram`
- `LMCache`
- `mooncake`
- `release-management`
- `Security`
- `SegmentCache`
- `sonic`
- `redis-dtoe`
- `reedsolomon`
- `rabitq`
- `monolith`
- `kaot`
- `Brotli4j`
- `isa-l`
- `KDADK-TOOLS`
- `QA`
- `protobuf`
- `KUAF`
- `snappy`
- `MicroservicesBench`
- `cmf`
- `ceph_BK`
- `ocf`
- `mesa`
- `Kbox-patches`
- `3FS`
- `vmi`
- `rocksdb`
- `hadoop`
- `cloud-native`
- `zstd`
- `lz4`
- `KAE`
- `hyperscan`
- `spdk`
- `gluten`
- `cloud-virtual`
- `vllm_router`
- `vllm-ops`
- `velox`
- `boostkit-agreements`
- `Redis`
- `folly`
- `infra`
- `.gitcode`
- `waas`
- `zlib`
- `sonic-cpp`
- `avx2ki`
- `kpglibc`
- `boostcore`
- `opencv`
- `ffmpeg`
- `libavif`
- `libwebp`
- `boostmedia`
- `boostcph`
- `boostvirt`
- `milvus`
- `boostdb`
- `boostsds`
- `omnistatestore`
- `omnistream`
- `omnioperator`
- `omniruntime`
- `knewpfordelta`
- `boostsra`
- `kvecturbo`
- `faiss`
- `hnswlib`
- `tensorflow-serving`
- `tensorflow`
- `community`
- `HPC-competitions`
- `src-openEuler-ubturbo`
- `src-openEuler-ub-pkg-manager`
- `sglang`
- `src-openEuler-ubs-comm`
- `src-openEuler-ubs-mem`
- `src-openEuler-ubs-io`
- `src-openEuler-ubs-virt`
- `src-openEuler-ubs-engine`
- `DeepSeek-V3-Sample`
- `hpckit-sample`
- `Infra`
- `src-openEuler-libvirt-python`
- `kunpeng-extension-for-pytorch`
- `kupl`
- `kutacc`
- `kuqcd`
- `kudnn`
- `bytedance-hikptool`
- `.atomgit`
- `HPCKit-Community`
- `openEuler-libvirt`
- `openEuler-qemu`
- `src-openEuler-ubctl`
- `src-openEuler-ubutils`
- `src-openEuler-cdma`
- `src-openEuler-memlink`
- `src-openEuler-ummu`
- `src-openEuler-umdk`
- `src-openEuler-sysSentry`
- `src-openEuler-obmm`
- `src-openEuler-Kernel`
- `hucx`
- `xucg`
- `hmpi`

</details>


<!-- SYNC_STATUS_END -->

## Setup

This sync-config follows the [community-mirror setup guide](https://github.com/huanglei0308/community-mirror/blob/main/docs/setup-guide.md).

### Required Secrets

| Secret | Description |
|--------|-------------|
| `SYNC_KUNPENG_GITCODE_TOKEN` | GitCode API token for reading source repos |
| `SYNC_KUNPENG_TOKEN` | GitHub token for creating/managing destination repos |
| `SYNC_KUNPENG_PRIVATE_KEY` | SSH private key for pushing to GitHub |

## Contact

huanglei 30082796
