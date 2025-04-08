</details>

**<details><summary>v5.4.4</summary>**

* BUG FIX - Add NGUI support to TextGetterCompatibilityMode
* BUG FIX - Fix broken Assembly-CSharp-firstpass detection in CallOrigin
* BUG FIX - Fix potential assembly comparison issue in TextGetterCompatModeHelper

</details>

</details>

**<details><summary>v5.4.3</summary>**

* Hotfix to minor regex performance improvement
* CustomTranslateEndpoint - Add EnableShortDelay and DisableSpamChecks settings

</details>

</details>

**<details><summary>v5.4.2</summary>**

* OS Independent Paths for MelonMod version by @PranitModak in #606
* Auto Translator Plugin Config accessible in android by @PranitModak in #612
* Translation scoping - if GetScopeFromComponent fails, use GetActiveSceneId instead of -1 by @Lmeks in #619
* Minor regex performance improvement by @Lmeks in #626
* Move XZipper from DotNetZip to SharpCompress by @ManlyMarco in #629

</details>

</details>

**<details><summary>v5.4.1</summary>**

*Fix change font crash when previous font is null
*Move all version constants into a global props file

</details>

</details>

**<details><summary>v5.4.0</summary>**

*Update DeepL supported languages according to API doc
*Update to BepInEx 6.0 BE-704
*Fix failing to get some Il2CppTypes silently and crashing later
*fix the outline style lost when overriding TextMeshPro Font

</details>

</details>

**<details><summary>v5.3.1</summary>**

*Use reflection to access Il2CppInteropManager.IL2CPPInteropAssemblyPath
*IL2CPP - Shim UnityEngine.Input to fix failing to find the type in some games
*Fix HandleInputSafe crashing in some games
*DeepL - Fix 404 error when calling GetClientState
*Allow DeepLTranslator supports auto
*Support Indonesian for DeepL Translate

</details>


</details>

**<details><summary>v5.3.0(FIX)</summary>**

* Fixed console management error

</details>

</details>

**<details><summary>v5.3.0</summary>**

* FEATURE - Added support for latest MelonLoader and BepInEx bleeding edge builds (only for IL2CPP, use stable release for Mono), also dropped support for earlier versions!
* FEATURE - Added 'PersistRichTextMode' to allow control over how text that is parsed as rich text during translation is persisted
* REGRESSION - Dropped support for pre-2017 Unity Engine versions for IL2CPP versions due to problems with new IL2CPP interop (may be re-added later)
* BUG FIX - Fixed some potential NullReferenceException occurrences
* UG FIX - Fixed potential bug during substitution replacements - thanks to TokcDK

</details>

</details>

**<details><summary>v5.2.0</summary>**

* FEATURE - Added support for Lingo Cloud - thanks to Kiles Duli
* BUG FIX - Fixed IL2CPP issue where plugin did not always use correct unhollowed paths for BepInEx

</details>