# sync-config

Kunpeng+BoostKit community mirror sync configuration — powered by [community-mirror](https://github.com/huanglei0308/community-mirror).

This repository runs an automated daily workflow that mirrors repos from:
- **gitcode/kunpengcompute** → **github/kunpengcompute**
- **gitcode/BoostKit** → **github/kunpengcompute**

<!-- SYNC_STATUS_START -->
**Last updated:** 2026-07-11T06:12:38Z
**Flow:** `gitcode/kunpengcompute+BoostKit` → `github/kunpengcompute`
**Status:** ⚠️ **24 repo(s) failed**

| Total | ✅ Synced | ❌ Failed | ⏭️ Skipped |
| ---: | ---: | ---: | ---: |
| 151 | 127 | 24 | 0 |

### 📊 Failure Summary

| Category | Count |
|----------|------:|
| 🚫 Branch Delete Refused | 11 |
| 📤 Push Rejected | 5 |
| 📥 Clone Failed | 3 |
| 🔵 File Too Large (>100MB) | 3 |
| 🔒 Pre-receive Hook Declined | 2 |

### ❌ Failed Repos

- **`Ultrascan`** — Cannot delete 'dev)' (current default branch on destination)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`pvm`** — remote: fatal: pack exceeds maximum allowed size (2.00 GiB)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`mysql-server`** — Cannot delete '8.0)' (current default branch on destination)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: Repo is very large (3018MB) — may have timed out<br>🔍 Cached: not found (download may have failed)

- **`snappy`** — Rejected by destination server pre-receive hook<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`hadoop`** — Cannot delete 'rel-2.7.7-aarch64)' (current default branch on destination)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`zstd`** — Failed to clone from source (network/auth/availability issue)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`KAE`** — Cannot delete 'master)' (current default branch on destination)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`hyperscan`** — Cannot delete 'aarch64)' (current default branch on destination)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`boostkit-bigdata`** — Rejected by destination server pre-receive hook<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`infra`** — Cannot delete 'main)' (current default branch on destination)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`boostsra`** — Cannot delete 'dev_for_doc_630)' (current default branch on destination)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`tensorflow`** — Cannot delete 'dev_for_doc_630)' (current default branch on destination)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`anolis-cloud-kernel`** — remote: fatal: pack exceeds maximum allowed size (2.00 GiB)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`velinux-kernel-dev`** — remote: fatal: pack exceeds maximum allowed size (2.00 GiB)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`velinux-kernel`** — remote: fatal: pack exceeds maximum allowed size (2.00 GiB)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`src-openeuler-gcc`** — gcc-12.3.0.tar.xz is 81.53 MB, exceeds GitHub 100 MB limit<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`src-openEuler-memlinkd`** — Failed to clone from source (network/auth/availability issue)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: Source repo not found or not accessible with current token<br>🔍 Cached: not found (download may have failed)

- **`src-openEuler-libummu`** — Failed to clone from source (network/auth/availability issue)<br>🔍 Source: Source repo not found or not accessible with current token<br>🔍 Destination: Source repo not found or not accessible with current token<br>🔍 Cached: not found (download may have failed)

- **`src-openEuler-libvirt`** — libvirt-9.10.0.tar.xz is 134.23 MB, exceeds GitHub 100 MB limit<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`src-openEuler-qemu`** — qemu-5.0.0.tar.xz is 59.53 MB, exceeds GitHub 100 MB limit<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`openEuler-Kernel`** — remote: fatal: pack exceeds maximum allowed size (2.00 GiB)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`hucx`** — Cannot delete 'huawei)' (current default branch on destination)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`xucg`** — Cannot delete 'huawei)' (current default branch on destination)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

- **`hmpi`** — Cannot delete 'huawei)' (current default branch on destination)<br>🔍 Source: accessible<br>🔍 Destination: exists<br>🔍 Cached: not found (download may have failed)

[🔍 View workflow logs](https://github.com/kunpengcompute/sync-config/actions)

<details>
<summary><b>✅ Synced Repos (127)</b></summary>

- `KVcache_lossless_compression`
- `gd-hnsw`
- `virt-efficiency`
- `CubeSandbox`
- `kacc_crypto`
- `OpenViking`
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
- `MicroservicesBench`
- `cmf`
- `ceph_BK`
- `ocf`
- `mesa`
- `Kbox-patches`
- `3FS`
- `vmi`
- `rocksdb`
- `cloud-native`
- `lz4`
- `spdk`
- `cloud-virtual`
- `vllm_router`
- `vllm-ops`
- `velox`
- `boostkit-agreements`
- `Redis`
- `folly`
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
- `kvecturbo`
- `faiss`
- `hnswlib`
- `tensorflow-serving`
- `community`
- `ub-dkms-build`
- `ub-os-component-dkms`
- `ub-buildin-patch`
- `src-elasticMem`
- `hpckit-testsuite`
- `hpckit-packtool`
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
- `src-openEuler-libcdma`
- `src-openEuler-umdk`
- `src-openEuler-sysSentry`
- `src-openEuler-obmm`
- `src-openEuler-Kernel`

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
