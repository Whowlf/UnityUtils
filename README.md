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
