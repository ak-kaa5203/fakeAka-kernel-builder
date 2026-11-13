# fakeAka Kernel Builder for POCO F4 (munch)

Automated GitHub Actions builder for **fakeAka Kernel** on the Xiaomi POCO F4 / Redmi K40S (**`munch`**), powered by the Qualcomm Snapdragon 870 (`sm8250`).

## 🚀 Features & Optimizations
* **Target Base:** Official LineageOS 23.2 kernel source (`android_kernel_xiaomi_sm8250`).
* **KernelSU Built-in:** Clean integration with official KernelSU (no manual patching required).
* **Thermal Charging Fix (Anti-Tekor):** Raised thermal step-charging floor so battery charges reliably even during intense gaming sessions.
* **Balanced EAS Scheduler:** Optimized CPU task placement for cooler temperatures and longer battery endurance.
* **TCP BBR:** Better packet pacing and lower latency for competitive mobile gaming.
* **Lightweight:** Stripped unnecessary debugging symbols (`CONFIG_DEBUG_KERNEL=n`, `CONFIG_SLUB_DEBUG=n`).
* **Packaging:** Automatically outputs an **AnyKernel3 flashable zip** and raw **`Image.gz` / `dtbo.img`**.

## 🛠️ How to Trigger the Build
1. Go to the **[Actions](../../actions)** tab in this repository.
2. Select **Build fakeAka Kernel (POCO F4)** on the left sidebar.
3. Click the **Run workflow** dropdown button, then confirm.
4. Wait ~7 to 10 minutes. When finished, download the **`fakeAka-Kernel-munch`** artifact!
