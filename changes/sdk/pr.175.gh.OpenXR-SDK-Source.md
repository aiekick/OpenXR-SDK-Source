Modifications to Azure DevOps build pipeline. Now builds UWP loader DLLs in addition to Win32 loader DLLs. No longer builds static loader libraries due to linkability concerns. Re-arranged release artifact zip to distinguish architecture from 32-bit or 64-bit.