# unity-docgen

Generate API docs for Unity games based on their assemblies

## Usage

1. Clone or download this repository
2. Install [DocFX](https://dotnet.github.io/docfx/) and [dnSpy](https://github.com/0xd4d/dnSpy)
3. Copy the `Assembly-CSharp.dll` assembly from the `${GameDir}/${GameName}_Data/Managed/` directory to the `src/` directory
4. Open the newly copied assembly using dnSpy, rename the root namespace (will appear as `{} -`) to `Game`, and save it
5. Edit the `index.md` file as you see fit
6. Run `docfx` (this might take a while depending on the size of the game)
