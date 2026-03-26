# GUID Regenerator

A Unity editor tool to regenerate GUIDs for your assets. Originally created by [Jeff Jadulco](https://github.com/jeffjadulco/unity-guid-regenerator).

## Installation

### VCC (VRChat Creator Companion)
1. Add `https://vpm.terrorized.dev/index.json` to your VCC community repositories
2. Search for "GUID Regenerator" in the package list
3. Click Add

### Unity Package Manager
1. Open Unity Editor > Window > Package Manager
2. Click "+" > Add package from git URL...
3. Enter `https://github.com/iTerrorized/dev.terrorized.guid-regenerator.git`

## Usage
1. Select one or multiple assets in the Project window
2. Right click > **Regenerate GUID** > choose **Files Only** or **Files and Folders**
3. Confirm the action in the dialog
4. Wait for the operation to complete
5. A report will be logged in the console

## Notes
- Scene files (.unity) are always skipped to prevent corruption
- Make sure you have a backup or version control before regenerating GUIDs
- This operation can take a long time on larger projects

## License
[MIT License](LICENSE.md) - Original work by Jefferson Jadulco
