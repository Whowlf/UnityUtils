# UnityUtils

Copy to clipboard function to string: 


using UnityEngine;

public static class ClipboardExtension
{
    public static void CopyToClipboard(this string str)
    {
        GUIUtility.systemCopyBuffer = str;
    }
}



Json.net for Unity
https://assetstore.unity.com/packages/tools/input-management/json-net-for-unity-11347
