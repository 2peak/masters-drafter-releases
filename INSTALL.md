# Install Masters Drafter

Masters Drafter is a Brawl Stars draft helper for Peak, wizza and labouch jr. It runs on a Mac with an **Apple Silicon** chip (M1 or newer). It will not run on an Intel Mac.

1. **Download.** Open the [releases page](https://github.com/2peak/masters-drafter-releases/releases), find the newest version, and download the file that ends in **`-mac.zip`**. Open the zip, then drag **Masters Drafter** into your **Applications** folder.
2. **Open it the first time.** Double-click the app. macOS will say it can't verify the app. Click **Done**. Then open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to Masters Drafter. Confirm with your password or Touch ID. You only do this once.
3. **If it says the app is "damaged"**, it isn't. Open **Terminal** and paste this line, then press Return, and open the app again:

   ```
   xattr -dr com.apple.quarantine "/Applications/Masters Drafter.app"
   ```
4. **Create your folder.** On the first screen, click **Create ~/Masters Drafter**. The app makes the folder for you.
5. **Wait a minute.** The stats download by themselves, and the draft screen opens when they arrive.

## After that

- The app checks for new versions when you open it. If one is ready it asks **Install now** or **Later**; nothing changes until you click. You can also use **Masters Drafter → Check for Updates…**.
- Your ratings, builds, favourites and draft notes stay in `~/Masters Drafter/team/` on your Mac.

Send other people the [releases page](https://github.com/2peak/masters-drafter-releases/releases), not the file: a copy sent by AirDrop or iMessage is more likely to show "damaged".
