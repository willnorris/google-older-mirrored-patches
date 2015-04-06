[Wine contributions](Wine.md) from 2006 to mid-July 2007.

| **Author** | **Date** | **Description** |
|:-----------|:---------|:----------------|
| Alexandre Julliard | 2007-07-19 | [kernel32: Move activation context creation to ntdll (based on a patch by Eric Pouech).](http://source.winehq.org/git/wine.git?a=commitdiff;h=64f6fdc57e930bbc9a218232bf4804f6872ccb2c) |
| Jacek Caban | 2007-07-19 | [ntdll: Added parsing of the asmv2:hash element in manifests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=63e4b943a9ec08172caeb9188d84756326dc74e3) |
| Jacek Caban | 2007-07-19 | [ntdll: Add parsing of dependencies in manifests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5efd2a35bd1d36fec3bb95582d801ed2623bc7a8) |
| Alexandre Julliard | 2007-07-19 | [ntdll: Add parsing of the version in manifests (based on a patch by Jacek Caban).](http://source.winehq.org/git/wine.git?a=commitdiff;h=5b0ab20787e36bf6a7e86a20eb730d69b59510e8) |
| Miko&#x0142;aj Zalewski | 2007-07-19 | [user32/tests: Simplify a test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=46a48c40add87b30daad043dfdb29ee2cb4e16c3) |
| Alexandre Julliard | 2007-07-19 | [ntdll: Move private data to make room in the TEB for the activation context data.](http://source.winehq.org/git/wine.git?a=commitdiff;h=44c9758d05a76244b88d13426feb5eff43c69417) |
| James Hawkins | 2007-07-19 | [msi: Implement reference counting for tables, manipulated with the HOLD and FREE ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=3b1ab76986afccaff08e9b649b42f27b60dd3e33) |
| Miko&#x0142;aj Zalewski | 2007-07-19 | [comctl32: toolbar: Test and fix invalid indexes passed in TB\_ISBUTTON\*.](http://source.winehq.org/git/wine.git?a=commitdiff;h=31be5005c633dee1476a77d93aa27e9c3f628c79) |
| Alexandre Julliard | 2007-07-19 | [ntdll: Skip xml comments in manifests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=272af8fa1eca695182384d8903b532c4a0f6b6f1) |
| Juan Lang | 2007-07-19 | [crypt32: Store hash algorithm ID along with other parameters when decoding a hash ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=22e7c2f38e2303671b3db38b31264c1cab0f1fb2) |
| Alexandre Julliard | 2007-07-19 | [ntdll: Added manifest lookup in global winsxs directory (based on a patch by Jacek ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=214fb6e84e1609b6e61c072719cda4124b667eb6) |
| Jacek Caban | 2007-07-19 | [ntdll: Added parsing of file elements in manifests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=16066acf8708716bb7944d53fe56941dccb4fd26) |
| Dmitry Timoshkov | 2007-07-19 | [rpcrt4: Fix the buffer bounds check.](http://source.winehq.org/git/wine.git?a=commitdiff;h=12d3905427796fd65f21673b77381442339ca00f) |
| Jacek Caban | 2007-07-19 | [ntdll: Store the windows directory too.](http://source.winehq.org/git/wine.git?a=commitdiff;h=125e710ff1d620ae8949f08cb22e040ef59c5d83) |
| Juan Lang | 2007-07-19 | [crypt32: Store (most) parameters of a decoded hash message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0e90cb9629e1bdfc979ff518b8b333712212e9f7) |
| Evan Stade | 2007-07-19 | [gdi32: Improved PolyDraw in path closed case.](http://source.winehq.org/git/wine.git?a=commitdiff;h=099bfbe1a4e0cd53fc6d22326740eb2356c3953e) |
| James Hawkins | 2007-07-19 | [msi: Add more tests for the ALTER command.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0169533be8d0a4f000e2cd264d04d1e71c19408a) |
| Huw Davies | 2007-07-19 | [wininet: Stub for InternetQueryFortezzaStatus().](http://source.winehq.org/git/wine.git?a=commitdiff;h=00631b24805faa445d321058963380a4486d07c7) |
| Huw Davies | 2007-07-18 | [wininet: Certain options of InternetQueryOption can take a NULL handle, so don't ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=d9bdf793fe32a69ef29aa40096b410a4a3c67d02) |
| Juan Lang | 2007-07-18 | [msi: Return FALSE from MsiGetMode for MSIRUNMODE\_OPERATIONS.](http://source.winehq.org/git/wine.git?a=commitdiff;h=955f5f3910a12fcc3e95983e3e46c079b45b5d23) |
| James Hawkins | 2007-07-18 | [Revert &quot;msi: Only call a custom action remotely if the type is msidbCustomActionTypeI ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=929acbcb7f019d89101c579e0348bc3ad5120a7e) |
| Juan Lang | 2007-07-18 | [wincrypt: Add more missing definitions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=834dbceadaacd45514865a99369f9fdee8fdb070) |
| Evan Stade | 2007-07-18 | [gdiplus: Added GdipClonePen.](http://source.winehq.org/git/wine.git?a=commitdiff;h=628c9a69c1ee6b2321d81866eab299aca03e95eb) |
| Huw Davies | 2007-07-18 | [wininet: Stubs for IsUrlCacheEntryExpired[AW](http://source.winehq.org/git/wine.git?a=commitdiff;h=3f2d93b51260fde45ca5e252044ab066d4acaead).] |
| James Hawkins | 2007-07-18 | [msi: Only double the size if the remote call is from MsiGetPropertyA.](http://source.winehq.org/git/wine.git?a=commitdiff;h=24e158e972e03c992389c259d05ab41ad1dcc1b5) |
| Evan Stade | 2007-07-18 | [gdiplus: Added GdipMultiplyMatrix.](http://source.winehq.org/git/wine.git?a=commitdiff;h=12e3eadd415a13c070673234fc97817ca53a704d) |
| Evan Stade | 2007-07-18 | [gdiplus: Added GdipGetPenDashStyle.](http://source.winehq.org/git/wine.git?a=commitdiff;h=024800cb9abc22e3a11749e76ee1c7eca8aa854c) |
| James Hawkins | 2007-07-17 | [vdmdbg: Add a stub implementation of VDMEnumTaskWOW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f2fc4d3a0f98754ac258d1e447f06d91c070cc07) |
| James Hawkins | 2007-07-17 | [msi: Only call a custom action remotely if the type is msidbCustomActionTypeInScript.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f2ae31000b6d6c105838fad36c17ba1fb1f5524b) |
| Evan Stade | 2007-07-17 | [gdiplus: Added GdipPathIterCopyData.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ef6c41663159c38eba19a166773c5b871ef5ec25) |
| Evan Stade | 2007-07-17 | [gdiplus: Added GdipSetPenDashStyle.](http://source.winehq.org/git/wine.git?a=commitdiff;h=daf00ab72a2b2e3a3a87f93ea312133ab4ab4ce9) |
| Evan Stade | 2007-07-17 | [gdiplus: Added GdipSetPenMiterLimit.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d59fe31e8b498fbe540bd101143e5bac985709a9) |
| Juan Lang | 2007-07-17 | [crypt32: Fix typo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c59d51ab24b5b508ca00fbc4c66ba82dfb9a3ef0) |
| Evan Stade | 2007-07-17 | [gdi32: Added PATH\_PolyDraw.](http://source.winehq.org/git/wine.git?a=commitdiff;h=96937e04a24d7e27b1bd2e97a730b67ad4ef2385) |
| Juan Lang | 2007-07-17 | [crypt32: Add a few tests for decoded message parameters.](http://source.winehq.org/git/wine.git?a=commitdiff;h=95bb1be2b72515c2c7dfa2dfd4f57fdd3f3e065b) |
| Evan Stade | 2007-07-17 | [gdiplus: Added GdipPathIterNextSubpath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=90ff0fdd6c813a762fd490aee9a369146243c014) |
| Juan Lang | 2007-07-17 | [crypt32: Use property list for decoded message parameters.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8df323f84a8d22fea63ee565065096cf67fd5f1d) |
| Juan Lang | 2007-07-17 | [crypt32: Remove a redundant line.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8cf82d8a0e7a6278a9a49294bb051f3c0664592d) |
| Juan Lang | 2007-07-17 | [crypt32: Fix a bad comment.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8099ff4bced2f5c7bf84d17150a503840899ae02) |
| Evan Stade | 2007-07-17 | [gdiplus: Added GdipAddPathBeziers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7e1917852968c61f964d055fa1c69df55ab222d9) |
| Juan Lang | 2007-07-17 | [crypt32: Move digested data encoding to encode.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=703a0f6fce49553fd66bc120f1d5128ea5250ead) |
| Evan Stade | 2007-07-17 | [gdiplus: Added GdipSetPenLineCap197819.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6893ef397ba63205bd102c5b262c943684fdf911) |
| Juan Lang | 2007-07-17 | [crypt32: Add tests for decoding a hash message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=60c6a9e3816822f481ba5383a64a21215f283326) |
| Evan Stade | 2007-07-17 | [gdi32: Added PolyDraw tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=578ff168b366a9248e8662e5c06c0f5ae3713441) |
| Juan Lang | 2007-07-17 | [crypt32: Implement getting content of a data message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4e2894493414da24429f557ae307791592ca216a) |
| Juan Lang | 2007-07-17 | [crypt32: Implement decoding hash messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=35abf3adf3d7daa0914df8d57c19fbaea2a00547) |
| Evan Stade | 2007-07-17 | [gdiplus: Export GdipSetPenLineJoin.](http://source.winehq.org/git/wine.git?a=commitdiff;h=18ee93b0c4826e3f23577f0ad25855e1659bb068) |
| Evan Stade | 2007-07-17 | [gdiplus: Added GdipPathIterRewind.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1182162dac3dd31e7ec47608b54200b9072062b8) |
| Evan Stade | 2007-07-17 | [gdiplus: Initial path iterator implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=085082897a47fec1113fad66b38d2129c1123acc) |
| Juan Lang | 2007-07-17 | [crypt32: Add a couple more parameter tests for hash messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=056b4f10dd0c7dd44457cc2115b6b8436edf903b) |
| Dmitry Timoshkov | 2007-07-16 | [shell32: Add a cache for queried shell folder interfaces.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f686cfab2feb9010efe82a932dc9f5904566c8ab) |
| Huw Davies | 2007-07-16 | [kernel32: Overlapped pipe tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e59a947c8860a07db11b047a75d897d2a0007217) |
| James Hawkins | 2007-07-16 | [msi: Load the AdminProperties stream if the package is an Admin package.](http://source.winehq.org/git/wine.git?a=commitdiff;h=dc3060c542661173937d3aa948f51ced7bbbdd5b) |
| Evan Stade | 2007-07-14 | [gdiplus: Added pixel offset mode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d6bd866df5ec0f4b253af14d677348967cc89138) |
| Evan Stade | 2007-07-14 | [gdiplus: Added GdipFillPath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d362b58ded69e08ae4ee20d21b238889b5f3ee0d) |
| Evan Stade | 2007-07-14 | [gdiplus: Added GpGraphics save/restore tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d13e1ba0e826a3acd59497978c98c150b24b8532) |
| Evan Stade | 2007-07-14 | [gdiplus: GdipSaveGraphics/GdipRestoreGraphics stubs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c760668cabb5a9f17a728bbfdb9fbb838a1e7a5b) |
| Evan Stade | 2007-07-14 | [gdiplus: Added interpolation mode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a87ce7ab9265f4b90d34f48dae1474e72330fbc2) |
| Evan Stade | 2007-07-14 | [gdiplus: Simplified GdipDrawPath by moving more of the code to the helpers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9e88347f4533a67df0b9cb119314b7cf5a8d4a8b) |
| Evan Stade | 2007-07-14 | [gdiplus: Added GdipSetPathFillMode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=68a3d94722fba2a7f245a2014d70aec424d8c99c) |
| Evan Stade | 2007-07-14 | [gdiplus: Added compositing quality.](http://source.winehq.org/git/wine.git?a=commitdiff;h=60cad2352230b588a7d3bdd62a0048cdfaad0721) |
| Evan Stade | 2007-07-14 | [gdiplus: Added smoothing modes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=53e17d2993f51b9fa8079ad5df6a1ff93d1955e7) |
| Evan Stade | 2007-07-14 | [gdiplus: Constructor tests for GpGraphics.](http://source.winehq.org/git/wine.git?a=commitdiff;h=05a7cef855331d8653ed528d88bfa26b50273ca9) |
| James Hawkins | 2007-07-13 | [msi: Fix three tests that were failing in Windows.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ed281b725aeaab3df51e8f6b438758878248b6f3) |
| Evan Stade | 2007-07-13 | [gdiplus: Use passed pen in GdipAddPathWorldBound.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e547ceb1f65e3367b0e665f71cd218355300f57a) |
| Evan Stade | 2007-07-13 | [gdiplus: Added GdipResetPath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d174bcc8a6955d1ad5f9493e1de679b0be89beee) |
| James Hawkins | 2007-07-13 | [msi: Fix automation.c compile for MSVC.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c7b53d37e15487ca7cd1fe141f4bcbde36c7c846) |
| Evan Stade | 2007-07-13 | [gdiplus: Added GdipAddPathPath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c41a77a358abeba54a629b87a1e4caed5db584d9) |
| Evan Stade | 2007-07-13 | [gdiplus: Added GdipSetPenLineJoin.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bcd0eda68701150fa98624d8b10fb1a221c7273a) |
| James Hawkins | 2007-07-13 | [msi: Add a test for installing from different current working directories.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ba257f0ceac03397702d75e3404408b0d692d71f) |
| Juan Lang | 2007-07-13 | [crypt32: Fix decoding sequences with extra trailing data.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8dcd9e4279ef6601440b92fd94a30e046be589da) |
| Juan Lang | 2007-07-13 | [crypt32: Implement decoding data messages (when opened in non-streaming mode).](http://source.winehq.org/git/wine.git?a=commitdiff;h=76061f403b0a2491803259ef30293fcdfa6a2d7d) |
| James Hawkins | 2007-07-13 | [msi: Fix compilation in MSVC.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6c940b9b49c7d2755b85c0fe265ec30aec1cf9a2) |
| Juan Lang | 2007-07-13 | [crypt32: Store crypt provider in decode message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6a07ca44420076056467742f780b445b91fd0af4) |
| James Hawkins | 2007-07-13 | [msi: Add a test for running an ADMIN install.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6805bf8acee22af3d3e7260229b3309d812b7d7b) |
| Evan Stade | 2007-07-13 | [gdiplus: Added GdipGetPathFillMode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=64035b308e978f03796cf5cc7e28fd3460889cd4) |
| Evan Stade | 2007-07-13 | [gdiplus: Added GdipAddPathPath test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=44691eefb452e5fdec54f87ca98413f9c90b3fc6) |
| Evan Stade | 2007-07-13 | [gdiplus: Added more GdipGetPathWorldBounds tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=41a9a838909d94e9e095748a3fb8437bfe495544) |
| Evan Stade | 2007-07-13 | [gdiplus: Improved GdipGetPathWorldBounds handling of both matrix and pen's effect ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=3dc17d2544570eb8db63fb2ac452318e1180bd3d) |
| Juan Lang | 2007-07-13 | [crypt32: Partially implement updating decode messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2cca297ba657c9ee03a1a7d271a4a0a4b6f599e3) |
| Juan Lang | 2007-07-13 | [crypt32: Add test showing extra trailing bytes should be tolerated in encoded data.](http://source.winehq.org/git/wine.git?a=commitdiff;h=01685bca0e3a5eedfda8f5b18a4f769b5450dffa) |
| Juan Lang | 2007-07-12 | [crypt32: Copy data in hash message update.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fef57dad46893908e4bf956bb5ad4f13340c72f4) |
| Evan Stade | 2007-07-12 | [gdiplus: Added draw\_polybezier error checking.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fa31217d6e831bf7b04f05d42e0c3dd58f496979) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipGetPathWorldBounds test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f9b0dac9f55ed876a0438450b3140e4f551870a8) |
| Juan Lang | 2007-07-12 | [crypt32: Don't check if msg is NULL, tests show native doesn't either.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f83da5cc0757a67b1e5fe3726014330774efdd69) |
| Evan Stade | 2007-07-12 | [gdiplus: Added basic matrix implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f28262b47da30f5d660bdc37244da81d4c3e1240) |
| Evan Stade | 2007-07-12 | [gdiplus: Fixed memory leak in GdipDeletePath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e9eceb5f313180e6bf9a5b893df9a9e64cbb9a5d) |
| Juan Lang | 2007-07-12 | [crypt32: Test opening hash messages to encode with streaming.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e6c339d076e38d169e042306519db4c1ae7b58e7) |
| Juan Lang | 2007-07-12 | [crypt32: Add more missing defines.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e3d6f771e85792833e96c57d8a05ad53405e3980) |
| Juan Lang | 2007-07-12 | [crypt32: Update comments about hash message version numbers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d1bd2ea907bb8d80b324794715416447d4dccff3) |
| James Hawkins | 2007-07-12 | [msi: Fix a copy and paste error.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cf3f442754cf3faca81d23186e6dc83eabed1370) |
| Juan Lang | 2007-07-12 | [crypt32: Simplify hash value tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c2f8191a648621f41831fb7e30c6898c5e994153) |
| Juan Lang | 2007-07-12 | [crypt32: Implement getting a hash message's hash value.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bb1246a51c5c8509ebfbcca324b7ad907739a67f) |
| Juan Lang | 2007-07-12 | [crypt32: Add open tests for hash messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b12072b72d7fad907ae204ca6bb0423f092aa840) |
| Juan Lang | 2007-07-12 | [crypt32: Implement streamed encoding of definite-length data messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=afaba37ed71ba3d4fc15cb7fb0d47f8ba869da00) |
| Juan Lang | 2007-07-12 | [crypt32: Add tests for updating hash messages opened to encode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ad975f672bf713da7c2af4d97f4ca68f191ca2c8) |
| Juan Lang | 2007-07-12 | [crypt32: Introduce an updated state, and use it to remove boolean &quot;begun&quot;.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a8e135f4c6b39ea6e0c4cee846815fb23333eeec) |
| Juan Lang | 2007-07-12 | [crypt32: Add a helper function to copy params.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a468e6f6c3be2d7de4c55e79ff7fe9f7fc16f870) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipDrawPath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9d5f568183340e53e82fb623fed0d04490f66112) |
| Juan Lang | 2007-07-12 | [crypt32: Relax a test, the specific error isn't so important.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9bdb084eb6945d349fcde825629c7a67ea18b9af) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipStartPathFigure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8a76d1e82c6c39ca946f42d01b6875cceb737002) |
| Juan Lang | 2007-07-12 | [crypt32: Add tests for retrieving the content of a non-finalized (detached) message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=880507d9069365317a2b7fc7435e8907b3af911f) |
| Juan Lang | 2007-07-12 | [crypt32: Implement retrieving a hashed message's content.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8599fd77487c9aa7c4a7fbda244a35fe953efc6f) |
| Evan Stade | 2007-07-12 | [gdiplus: Updated GdipDrawLines to use SaveDC()/RestoreDC()/end caps.](http://source.winehq.org/git/wine.git?a=commitdiff;h=852aac8b54b12812187d5c4dc558b5fb52cbcc07) |
| Juan Lang | 2007-07-12 | [crypt32: Implement getting hash message version.](http://source.winehq.org/git/wine.git?a=commitdiff;h=804b9d71656d1b478dc1b2ffad62a65e04b1e618) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipGetPathWorldBounds.](http://source.winehq.org/git/wine.git?a=commitdiff;h=78510e70e76e8fe40a292c9dde79a4f1fa2f45f3) |
| Juan Lang | 2007-07-12 | [crypt32: Partially implement updating hash messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=739cc08b3bb95b7f5a320c946f2ecb002e734f36) |
| Juan Lang | 2007-07-12 | [crypt32: Add tests for hash message encoding.](http://source.winehq.org/git/wine.git?a=commitdiff;h=72b8f8325f5df78f350137b7189281ef870edbd8) |
| Evan Stade | 2007-07-12 | [gdiplus: Added draw\_polyline error checking.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6f4ab5282411cde3298fa1c036004f2894350d73) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipAddPathArc.](http://source.winehq.org/git/wine.git?a=commitdiff;h=69fa7457e5d746b71c8fef1f2ffb1924a5bc8d35) |
| Juan Lang | 2007-07-12 | [crypt32: Introduce an algorithm id encoding function that encodes missing parameters ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=678fb8ac14b3062a3221247f66075c5ca02862de) |
| Juan Lang | 2007-07-12 | [crypt32: Test updating hash messages with NULL stream output function.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5cb26d8e58b0640abccec28b3ee649c9bed6cdeb) |
| Evan Stade | 2007-07-12 | [gdiplus: Changed the way the direction of the endcap is calculated to make LineCapArr ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=55d70e894cd70f69d313771e8f5dedd56cce4bc0) |
| Evan Stade | 2007-07-12 | [gdiplus: Moved two inline helpers to the header.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4a8a1b423c4d8984e61eae9efff7cbdf846b79f1) |
| Juan Lang | 2007-07-12 | [crypt32: Make some encoding functions available outside encode.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=48afa16386c47a27b9b230dfb726959418c9d28a) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipTransformMatrixPoints.](http://source.winehq.org/git/wine.git?a=commitdiff;h=47a605ef9bd2bae60ba74d5f60a2bd1792dfab9e) |
| Evan Stade | 2007-07-12 | [gdiplus: Updated GdipDrawArc to use SaveDC()/RestoreDC()/line caps.](http://source.winehq.org/git/wine.git?a=commitdiff;h=40f2273f0354ce403684623449379a0da388e98a) |
| Juan Lang | 2007-07-12 | [crypt32: Detached hash messages don't contain the content, so don't make a copy of it.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3ffb4b1c4871011631a1d580fd77aa0e5fc7cbb8) |
| Juan Lang | 2007-07-12 | [crypt32: Add a stub hash message implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3c15f98b77d9f1f9dd671b16c8b0e8744a8b241c) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipTransformMatrixPoints test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=37d91b04f3b7abf2c6876c75d7e3e0bfdd422dd2) |
| James Hawkins | 2007-07-12 | [msi: Reload properties as they may have been changed by a transform.](http://source.winehq.org/git/wine.git?a=commitdiff;h=30fc5602def216483177150160bd45c90fb20d64) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipAddPathArc test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1f7cfb1dc829bcec72b3af324ef4c125cd82de91) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipTransformPath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1f1ecfb2b51bb0cab790c9c83cd8cbd8fb20d013) |
| Juan Lang | 2007-07-12 | [crypt32: Add tests for getting hash message params.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1745d8a7285a9555ef3617c96fadc8b4c8dadb25) |
| Juan Lang | 2007-07-12 | [crypt32: Change finalized from a boolean to a state and use it to simplify message ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=09c4faf159c1a6897926ea559f687aa552b26d46) |
| Evan Stade | 2007-07-12 | [gdiplus: Added GdipCreateMatrix2 test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=05450b036611a8b7c5b5430bf89389dd397dda41) |
| Huw Davies | 2007-07-11 | [kernel32: Swap incorrect use of buffers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f2894533d561bb1c42872e54eef9599251e450d7) |
| Lei Zhang | 2007-07-11 | [winex11.drv: Remove old dnd code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d0e068744a02c6a66685aec8db72a23db9d05962) |
| Juan Lang | 2007-07-11 | [rsaenh: Get rid of the hash idle state, native doesn't behave as though it has one.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cd3954e7fdeda223b81524a1f41839af90408b31) |
| Evan Stade | 2007-07-11 | [gdiplus: Changed calls to floor to floorf.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6544d9ee3e149234991406f188b357dd0d9d253b) |
| James Hawkins | 2007-07-11 | [msi: Fix current \_Property table tests and add more tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5a8e0e8c1dad256c1b47885b889e63472879d516) |
| Miko&#x0142;aj Zalewski | 2007-07-11 | [msxml3/tests: Avoid a crash that happens on some native systems.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3c29359286f2e0db5559862ef1c15cc679ce2607) |
| Huw Davies | 2007-07-11 | [kernel32: SetNamedPipeHandleState() is a stub, so for now don't check its return ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=154389ce8e98f2f1639c3d03490174ec170a2d34) |
| James Hawkins | 2007-07-11 | [msi: Add tests for adding properties in a transform.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1093eb83cd37c57895154afe21706333421fcae8) |
| James Hawkins | 2007-07-11 | [msi: Add tests for adding properties with a transform during an install.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0f6aaf86bd52ec382bc6ecb7982e7701e484c553) |
| Evan Stade | 2007-07-10 | [gdiplus: Added constructor and destructor test for gdiplus paths.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fec9e5e8031ba35e840ad2804027e29d4d2b9c5f) |
| James Hawkins | 2007-07-10 | [msi: Check for NULL transform, as there may be no transforms for the \_Columns or ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=f0b97cb1e175eb82fc05821f5e72d9181f046989) |
| Miko&#x0142;aj Zalewski | 2007-07-10 | [comctl32: toolbar: The iImage in TBN\_GETDISPINFO should be initialized to -1.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e66523e19bf17f4b12852ce6d8168a21159fb139) |
| James Hawkins | 2007-07-10 | [msi: Match the changes made by the hand-generated and API-generated transforms.](http://source.winehq.org/git/wine.git?a=commitdiff;h=dfa1b1299cbdea6f22016d03788532abb65718e7) |
| Evan Stade | 2007-07-10 | [gdiplus: Added a test for GdipAddPathLine2.](http://source.winehq.org/git/wine.git?a=commitdiff;h=da23ed6e0f95893b069f0f0ede16002a0970c31c) |
| Evan Stade | 2007-07-10 | [gdiplus: GdipDrawCurve2 now uses SaveDC()/RestoreDC() and end caps.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b72dc0df9d534322b74efa493d6e73793cc20f62) |
| Evan Stade | 2007-07-10 | [gdiplus: Updated draw\_pie to use SaveDC/RestoreDC.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a4fff71454ac04b7b3aa4f4a8f1dbf41505b1617) |
| James Hawkins | 2007-07-10 | [msi: Test adding columns with data in a transform.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9285351ad3b088ff126fde7f62648348682c4d40) |
| James Hawkins | 2007-07-10 | [msi: Delete msifile after the tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5af06dec83870d73ba0234ec25e97a8a7fdb8385) |
| Miko&#x0142;aj Zalewski | 2007-07-10 | [comctl32: toolbar: We should send TBN\_GETDISPINFOW even for ANSI controls (with testc ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=5507a073c5e1be9101440c110d2d1e7092a4d293) |
| Alexandre Julliard | 2007-07-10 | [winedump: Add RT\_MANIFEST resource type.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4da30bfcfc7607bb4ddd057900120092fd46786c) |
| Alexandre Julliard | 2007-07-10 | [include: Add some definitions for manifest resources.](http://source.winehq.org/git/wine.git?a=commitdiff;h=41db95323d67cae850f6d35ee1ffba16bc0da349) |
| Lei Zhang | 2007-07-10 | [start.exe: Put double quotes around arguments with spaces.](http://source.winehq.org/git/wine.git?a=commitdiff;h=30a22664e66f8625522e734741979977c6f54e7b) |
| Evan Stade | 2007-07-10 | [gdiplus: Make LineCapArrowAnchor look more like it does in windows.](http://source.winehq.org/git/wine.git?a=commitdiff;h=30084db2ce2ba20800610726954533eddb9abcc7) |
| Evan Stade | 2007-07-10 | [gdiplus: Fixed bug in GdipGetPathPoints().](http://source.winehq.org/git/wine.git?a=commitdiff;h=1fc841f6555d9700499dcc59adf0e6b1d6bc5795) |
| Juan Lang | 2007-07-10 | [crypt32: Implement CryptSIPLoad.](http://source.winehq.org/git/wine.git?a=commitdiff;h=19c3a09ba8160c3b654f39681f6abdc550ab5d39) |
| James Hawkins | 2007-07-10 | [msi: Handle adding columns in transforms.](http://source.winehq.org/git/wine.git?a=commitdiff;h=17ba74195bec3d384539249a4bf7de659121041e) |
| Evan Stade | 2007-07-10 | [gdiplus: Updated GdipDrawRectangleI.](http://source.winehq.org/git/wine.git?a=commitdiff;h=14e0df1fa0c0225d8de4d997b64aaec74963dd9a) |
| Evan Stade | 2007-07-10 | [gdiplus: Fixed a bug in helper function draw\_polybezier.](http://source.winehq.org/git/wine.git?a=commitdiff;h=14c7466c9f2d726741e9e9f9cf6a8befc527a147) |
| Juan Lang | 2007-07-09 | [crypt32: Add more tests for opening a data message for encoding.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fd05fe0d132a503b00aebd263aab46e63ddcfaa7) |
| Juan Lang | 2007-07-09 | [crypt32: Test and fix CryptMsgGetParam for streamed messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e557d36320bad7768271e1774bb3e9acbb7bc8c2) |
| Juan Lang | 2007-07-09 | [crypt32: Pass function pointers to CryptMsgBase\_Init rather than rely on callers ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=dc63bf2de396cfa3db64a13f8bc54fda9075b2fb) |
| Juan Lang | 2007-07-09 | [crypt32: Add tests for streamed encoding of data messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b18b05f53c08ae1ffc87c83447b9e562ea6bacd0) |
| Juan Lang | 2007-07-09 | [crypt32: Add some tests for updating decode messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=acc0bec41ff75632442e38725e86a20f884e57fd) |
| Juan Lang | 2007-07-09 | [crypt32: Test that inner content OID is ignored for data messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=aa99cf8ec04801945f4c11f880f6fe64ec6c9dc8) |
| Juan Lang | 2007-07-09 | [crypt32: Implement getting the type of a decode message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8ca755915b6f677d51837b5e00658617474bd68e) |
| Juan Lang | 2007-07-09 | [crypt32: Make a copy of a passed-in stream info rather than assuming the pointer ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=7e65d9439cd0141459cf3f0f3e1553c66518a71c) |
| Juan Lang | 2007-07-09 | [crypt32: More decode message update tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=685d7e799a84dfa51e79e56594a4bd1107403a0b) |
| Juan Lang | 2007-07-09 | [crypt32: Add a stub decode message implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=656d960dd4b01e1ef1f293e1214f8b1629c7c2e6) |
| Juan Lang | 2007-07-09 | [crypt32: Implement CryptSIPGetSignedDataMsg, CryptSIPPutSignedDataMsg,](http://source.winehq.org/git/wine.git?a=commitdiff;h=1d5a8b2f781e2a4a8894c84d2590a8e198a24cea) |
| Evan Stade | 2007-07-07 | [gdiplus: Rendering of linecaps.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5128e5dc58c7e2d0f6c8550a06a38337604661b6) |
| Evan Stade | 2007-07-06 | [gdiplus: Added GdipAddPathLine2.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e4118c1847e750ccfcd8059c6ff009f43233ea7e) |
| Evan Stade | 2007-07-06 | [gdiplus: Added GdipClosePathFigures.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d0ba8711ff24ee59df9d87423ddb5b85f8c93186) |
| James Hawkins | 2007-07-06 | [msi: Handle remote calls to MsiFormatRecordW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cba1b1e1f480cecc6e3bca4fe2978efb2585a800) |
| James Hawkins | 2007-07-06 | [msi: Forward MsiFormatRecordA to MsiFormatRecordW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ba4919912c0087ea614f0f55d31c7dfcdd809427) |
| Evan Stade | 2007-07-06 | [gdiplus: Added GdipClosePathFigure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8c1291974450850de52f07f66f56a5597929955e) |
| Evan Stade | 2007-07-06 | [gdiplus: Added GdipGetPointCount.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8a114adefe34e2ded326094a7087c13547648cea) |
| James Hawkins | 2007-07-06 | [msi: Handle remote calls to MsiEvaluateCondition.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6b97f8905dc9435b8018a297472b4f4dbec315a3) |
| Evan Stade | 2007-07-06 | [gdiplus: Added linecap rendering for GdipDrawBezier.](http://source.winehq.org/git/wine.git?a=commitdiff;h=69a807c6a9a5729c1c8458f92a7ac39754287572) |
| Evan Stade | 2007-07-06 | [gdiplus: Added SetPenEndCap.](http://source.winehq.org/git/wine.git?a=commitdiff;h=68ba30f4333ac468b04656016fc7355ab0bfb2e8) |
| Evan Stade | 2007-07-06 | [gdiplus: Public declaration of GdipSetPenEndCap.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5dc8dee76d21957b72d89ff6299b84f34d96b56c) |
| James Hawkins | 2007-07-06 | [msi: Fix use of BSTRs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=29ce520df98005c8b6e74145a9097b3020e91872) |
| James Hawkins | 2007-07-06 | [msi: Enable remote custom actions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1647de570bedb0052359075367e49dbae5ecc7b6) |
| Evan Stade | 2007-07-06 | [gdiplus: Added GdipGetPathPoints.](http://source.winehq.org/git/wine.git?a=commitdiff;h=08784f371762133fb57a6329926345899856d3cb) |
| Evan Stade | 2007-07-06 | [gdiplus: Added GdipGetPathTypes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=06206fc4a5a8cbfa31b40fa570f2572f06c27217) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiSetTargetPath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f935e94adffcdf834972a1ca21649854fcbb05e3) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiSetFeatureState.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f45b3ce60e4282d239b9e5396ed180af41557390) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiGetMode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c96f1d524b50d4a1506c5ce4c25f8e624221f617) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiSetInstallLevel.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c6741d83c6476a7862c148f8ad2cb5acd27563a3) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiProcessMessage.](http://source.winehq.org/git/wine.git?a=commitdiff;h=be5eec45b5f68aab9469bfc70602ec554e8057f1) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiGetTargetPath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b7479be1bb24257533447bbae049cc13d41bfdc8) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiSequence.](http://source.winehq.org/git/wine.git?a=commitdiff;h=99714f12cb08fb40521f6d8e12fab2ca7a40b622) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiSetComponentState.](http://source.winehq.org/git/wine.git?a=commitdiff;h=82b0066f706631425d76fa15d8c5784ab29e8044) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiGetFeatureState.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7d93e1a2a5a782f10c5d36d11724584b06fe5dc5) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiGetSourcePath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=582be6a73a11a6bc3b47fc9c7da73c14aa0c0a9b) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiGetLanguage.](http://source.winehq.org/git/wine.git?a=commitdiff;h=569ea392a7ccc5ced3e4b6fd96ffdc10d04e4c00) |
| Evan Stade | 2007-07-04 | [gdi32: Don't access DC in PolyDraw after releasing handle.](http://source.winehq.org/git/wine.git?a=commitdiff;h=53e05015f6d5bfb6c2418775688143c7894b4459) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiGetComponentState.](http://source.winehq.org/git/wine.git?a=commitdiff;h=254e27ad31dfb0e34b5474cd831baf73eef2f5c8) |
| James Hawkins | 2007-07-04 | [msi: Handle remote calls to MsiDoAction.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0f321c0af9503219ab8667ce0a84bb75d38fc602) |
| James Hawkins | 2007-07-03 | [msi: Add the IWineMsiRemotePackage interface.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f9001058b07b9d77b447ef3dbfee0ee5774a16c6) |
| James Hawkins | 2007-07-03 | [msi: Handle remote calls to MsiGetActiveDatabase.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e4658e05f2a930caef6d1c45e3605e49503b12bf) |
| James Hawkins | 2007-07-03 | [msi: Add tests for MsiQueryFeatureState.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ceb4e6d4ef0e7ae7950783254c438595df967e1a) |
| Evan Stade | 2007-07-03 | [gdiplus: Call EndPath() in GdipDrawLineI in case there is an open path.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c60c030c95b17e089fd9b1302c5391fbf708413c) |
| James Hawkins | 2007-07-03 | [msi: Add the IWineMsiRemoteCustomAction interface.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bc4750ff75f83498693cf420d513112c16617420) |
| James Hawkins | 2007-07-03 | [msi: Only publish the product if at least one feature is to be installed.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a2df31aea1746fcf067c77af56453100077a336f) |
| James Hawkins | 2007-07-03 | [msi: Return INSTALLSTATE\_ADVERTISED if the component list is empty.](http://source.winehq.org/git/wine.git?a=commitdiff;h=73e0a87477c4b0fe792988061397a5241b72a985) |
| James Hawkins | 2007-07-03 | [msi: Unpublish the product when it is entirely removed.](http://source.winehq.org/git/wine.git?a=commitdiff;h=624bbbe78a68598003eb906ddc1839a250bed340) |
| James Hawkins | 2007-07-03 | [msi: Delay publishing of the SourceList until the PublishProduct action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5e46fc9019dce5befe72b50695b8d309aba4f65f) |
| James Hawkins | 2007-07-03 | [msi: Add tests to show when the SourceList is published to the registry.](http://source.winehq.org/git/wine.git?a=commitdiff;h=56129f252c6180be1f75c4698b6bb759344d4490) |
| James Hawkins | 2007-07-03 | [msi: Handle remote calls to MsiGetProperty.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4de8247c5a8b914483f589455fa89d9c9313eaa1) |
| James Hawkins | 2007-07-03 | [msi: Handle remote calls to MsiSetProperty.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4d668e06a26cdd68fad87e35d0d11008e5efe859) |
| James Hawkins | 2007-07-03 | [msi: Read the components state directly from the registry.](http://source.winehq.org/git/wine.git?a=commitdiff;h=39a5638268095be901f4a0103c2be51959cd86ca) |
| James Hawkins | 2007-07-03 | [msi: Return INSTALLSTATE\_BADCONFIG if we can't decode the first component.](http://source.winehq.org/git/wine.git?a=commitdiff;h=34f6af95b4cafc25f06a1ca85c6eb555c34966b5) |
| James Hawkins | 2007-07-03 | [msi: Open the correct key and return INSTALLSTATE\_ADVERTISED if it's missing.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1130d5909b102581fb669c7ed3339e657e85cb5f) |
| James Hawkins | 2007-07-03 | [msi: Set the WindowsInstaller value in RegisterProduct instead of PublishProduct.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0e44e090c591f485776c7e3898dec5a9e7296f85) |
| James Hawkins | 2007-07-03 | [msi: pcchValue represents the length of szValue in TCHARS, not bytes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0cd708e7f5eb91d6ec8c7448180451cf400f062e) |
| James Hawkins | 2007-07-03 | [msi: PackagePath must also include the package name.](http://source.winehq.org/git/wine.git?a=commitdiff;h=08443b3bf7f5535dc438b64e9f8aeb9976b64424) |
| James Hawkins | 2007-07-03 | [msi: Add support for the MSICODE\_PATCH option.](http://source.winehq.org/git/wine.git?a=commitdiff;h=04c67c2a1cce0986a2587b9605092b9eef317a4e) |
| Evan Stade | 2007-07-02 | [gdiplus: Use SaveDC, RestoreDC in GdipDrawLineI.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d9ef172e04397ffe4a14ba2c87a210e3ad87f45a) |
| Juan Lang | 2007-06-29 | [crypt32: Implement getting content for data messages opened to encode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f75b86f02be0d3caa030b6c89dc66e6338d5717c) |
| Juan Lang | 2007-06-29 | [crypt32: Accept OSS errors as well.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f575d8569bb73dc843ab30daa7c7b305bb813159) |
| Juan Lang | 2007-06-29 | [crypt32: Accept ERROR\_INVALID\_PARAMETER in addition to ERROR\_PATH\_NOT\_FOUND (and ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=ef134dc70335a76b38d62d52e94c23bd55d2932e) |
| Juan Lang | 2007-06-29 | [crypt32: Accept OSS errors.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e64e66c41d0fd9d0c390308db1554a75f6d69bd0) |
| Juan Lang | 2007-06-29 | [crypt32: Add tests for data message encoding.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d1f379340a5d9936c76db78778fc4ba36e6472a4) |
| James Hawkins | 2007-06-29 | [msi: Return ERROR\_SUCCESS if the PackageName property is not present.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c26505b7016fa593c46a1e9666ba97ceee7f9cef) |
| Juan Lang | 2007-06-29 | [crypt32: Don't fail when CryptVerifyCertificateSignatureEx is missing, use skip (and ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=85eeccc5857df12dbbce4e78b9c7b5beb6c67184) |
| Juan Lang | 2007-06-29 | [crypt32: Implement CryptMsgUpdate for data messages opened to encode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=74bf713be79c40be97c37f2a83257e04447300e7) |
| James Hawkins | 2007-06-29 | [msi: Implement MsiSourceListGetInfoA.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6cc2f0f4025fcae3fb58ae816bef4c68d8ac48a1) |
| Juan Lang | 2007-06-29 | [crypt32: Use skip to avoid failures where support is missing.](http://source.winehq.org/git/wine.git?a=commitdiff;h=68b052057b28f86314538478d0f9834800faaf41) |
| James Hawkins | 2007-06-29 | [msi: Validate MsiSourceListGetInfo parameters.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3e56d78f2eb38b186abaac482c009cef8c4222e6) |
| James Hawkins | 2007-06-29 | [msi: Return ERROR\_BAD\_CONFIGURATION if the SourceList key does not exist.](http://source.winehq.org/git/wine.git?a=commitdiff;h=381b915b475f12e6ecd5fb14bb8fda05c52f2dac) |
| Juan Lang | 2007-06-29 | [crypt32: Implement getting bare content for data messages opened to encode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=263f424c3b27a99553d7d564b9032db17018dd2e) |
| James Hawkins | 2007-06-29 | [msi: Add tests for MsiSourceListGetInfo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1ff40d15587a9c41d2e22a1ae2abb540635a026a) |
| Juan Lang | 2007-06-29 | [crypt32: Accept ERROR\_BADKEY in addition to ERROR\_INVALID\_HANDLE.](http://source.winehq.org/git/wine.git?a=commitdiff;h=11e6717e667db19fb5b2ffd4315fba76832809e1) |
| Juan Lang | 2007-06-29 | [crypt32: Add a stub get param function for data messages and remove stub message ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=0546cf1a696125b82843959a5d0d7de36a5abb40) |
| Juan Lang | 2007-06-28 | [crypt32: Stub CryptMsgOpenToEncode for data messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fa0f5bd066b6514a14e877fad9dd7836ef5f4ae0) |
| Juan Lang | 2007-06-28 | [crypt32: Test CryptMsgGetParam for data messages opened to encode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e829833986de44ee1ab950594589243dce6815c0) |
| Juan Lang | 2007-06-28 | [crypt32: Add a get param function, use it to implement CryptMsgGetParam.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d5e784bdaf7641eafd3bed773f708f39a1eea8e0) |
| Juan Lang | 2007-06-28 | [wincrypt: Add missing message flags and parameters.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c56177a8e945f76d15a67d7b55b23eb2275d1a98) |
| Juan Lang | 2007-06-28 | [crypt32: Test CryptMsgUpdate for data messages opened to encode.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bd05e2abe33d042675b56a3d066a3762463e15ca) |
| James Hawkins | 2007-06-28 | [msi: Ignore invalid conditional expressions when checking the launch conditions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bafc4dc3854f59ec0e07aaa202a260c3cf56c5eb) |
| Juan Lang | 2007-06-28 | [crypt32: Add base message type and use it to implement CryptMsgDuplicate and CryptMsg ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=b790a09efbd02369b2e3bf0db8a946a15e0a502c) |
| Juan Lang | 2007-06-28 | [crypt32: Add a finalized member to message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b6bf594aa571731392acace33cab4ae731a4dbc5) |
| Juan Lang | 2007-06-28 | [crypt32: Test CryptMsgOpenToEncode for data messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a581855d263ad259ba63e19856a55a8b0cd420a0) |
| Juan Lang | 2007-06-28 | [crypt32: Don't return fake HCRYPTMSG from CryptMsgOpenTo\*.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6c054f057b75cf0257d78d50f70db5eafb5fc658) |
| Juan Lang | 2007-06-28 | [crypt32: Add an update function, use it to implement CryptMsgUpdate.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5db6b1cc962d0ab8c3bb6e9f05ef534437c91af3) |
| Juan Lang | 2007-06-28 | [crypt32: Add basic tests for CryptMsg functions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3de0e4ac48bedb67c0402ad8ad1de38521eecc83) |
| James Hawkins | 2007-06-28 | [msi: Add tests that show '!=' is not a valid conditional expression operator.](http://source.winehq.org/git/wine.git?a=commitdiff;h=219857f831616811aa36275d1c6c0098b4ce6a2f) |
| Juan Lang | 2007-06-28 | [crypt32: Store stream info in message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=203849d75d0a62e1b1b970cb73941755642f8123) |
| Juan Lang | 2007-06-28 | [crypt32: Add basic parameter checking to CryptMsgOpenTo\*.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1c837f16ace9217bcad618149c85d6932542fde6) |
| James Hawkins | 2007-06-27 | [msi: Set the WindowsInstaller value of the UserData product key when publishing the ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=c18b77557d60017ef3f3c2eea5782bae17126006) |
| James Hawkins | 2007-06-27 | [msi: Use the correct registry key when detecting a published product.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7da89f48fd44c54e8b963e94b5f69d88b6334c57) |
| James Hawkins | 2007-06-27 | [msi: Add support for remote handles.](http://source.winehq.org/git/wine.git?a=commitdiff;h=46158e034cb0f17f32d5c7516df96f1a5ded6093) |
| James Hawkins | 2007-06-27 | [msi: Any value of WindowsInstaller besides 0 means the product is installed.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3bf32f27005a0e529d0ef614d407a85fee8f5238) |
| Evan Stade | 2007-06-27 | [gdi32: Added missing call to GDI\_ReleaseObj.](http://source.winehq.org/git/wine.git?a=commitdiff;h=39357c4ba6a862bbe257b6ac9691ee40564e9b81) |
| James Hawkins | 2007-06-27 | [msi: If the UserData product key exists, but the user product key doesn't, the produc ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=24ede2f9e602b24080f47134055f9a1e540f487c) |
| Dan Hipschman | 2007-06-26 | [widl: Check for interface pointers in pointer handling.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fcebe48cadcc1abfca71f1a78bba06bd0c858fca) |
| Lei Zhang | 2007-06-26 | [comctl32: Reduce duplicate code between PROPSHEET\_CollectSheetInfoA/W.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f4dd14abc6ddf7b1b1f50bf75df8b857af85f6aa) |
| Dan Hipschman | 2007-06-26 | [rpcrt4: Allow enums as union switch types.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ea7b1694de36742f0b3b356a6bebf5d181619583) |
| James Hawkins | 2007-06-26 | [msi: Validate MsiQueryProductCode parameters.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e92f66558a8f415cee051d8752438726dbd64bc1) |
| Lei Zhang | 2007-06-26 | [comctl32: Determine if PSH\_PROPSHEETPAGE is set once.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e3b80a0d882239a7bebb03ac49ee4698c1e9be43) |
| James Hawkins | 2007-06-26 | [msi: Add tests for MsiQueryProductState.](http://source.winehq.org/git/wine.git?a=commitdiff;h=db318ec9afd96b49950dc8f06dcfe6586f135263) |
| Dan Hipschman | 2007-06-26 | [widl: Check for user types when calculating buffer size.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ab22b4b3d45717831c4f5ce82de2e0705d0735d4) |
| James Hawkins | 2007-06-26 | [msi: Add tests for publishing and unpublishing products, features, and components.](http://source.winehq.org/git/wine.git?a=commitdiff;h=90e9722ecb03529deab340d22018cdfdbea560c7) |
| Dan Hipschman | 2007-06-26 | [widl: Fix crash dealing with anonymous unions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=704f2868ed0c1350a08a2991b7db4cf086ef3389) |
| Dan Hipschman | 2007-06-26 | [widl: Get simple enums working.](http://source.winehq.org/git/wine.git?a=commitdiff;h=512c36cae62fa0d45ac1997abf4eb0149ce264cd) |
| Dan Hipschman | 2007-06-26 | [widl: Allow enums as union switch types.](http://source.winehq.org/git/wine.git?a=commitdiff;h=46222aee6ea7577ba060d1907d29ca5a8651a524) |
| James Hawkins | 2007-06-26 | [msi: If the user product key exists, the product's state is advertised.](http://source.winehq.org/git/wine.git?a=commitdiff;h=15823e1acfab45d975a0239efd9fafa7e8dd741e) |
| Lei Zhang | 2007-06-26 | [comctl32: Reduce duplicate code between PropertySheetA/W.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0cbee494b34354b533346eece60e03f6cdaf9cab) |
| Dan Hipschman | 2007-06-26 | [rpcrt4/tests: Wrap a try/except block around tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=076a6206ff9598af97e940b62b8b629da4758e6d) |
| James Hawkins | 2007-06-25 | [msi: Add a stub implementation of MsiQueryComponentStateA.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ee89cfca534679d72b23a79165b6a74e5fc19b40) |
| James Hawkins | 2007-06-25 | [msi: Fetch the volume name when getting disk info.](http://source.winehq.org/git/wine.git?a=commitdiff;h=71d7da11707b5ccdb7aec9664c01aaa56c9e349f) |
| James Hawkins | 2007-06-25 | [msi: Reference count the custom action data to avoid freeing the data by another ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=4c3e4ba02907f780d7bb78acc646115b5792765d) |
| Evan Stade | 2007-06-23 | [gdiplus: Fix broken graphics path constructor.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6baacf61a857a7f9c471005cb12553f8d37a558e) |
| Evan Stade | 2007-06-23 | [gdiplus: Tidy up graphics constructor.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6490dadb2396b8b495e681b6bbfd2a22acac355b) |
| Evan Stade | 2007-06-23 | [gdiplus: Fix erroneous pen error checking.](http://source.winehq.org/git/wine.git?a=commitdiff;h=02efd4bbf1afdc9cba8c7e824d85bb7f7b6a7319) |
| Evan Stade | 2007-06-21 | [gdiplus: Implemented GdipDrawLines.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f6f04f6e0ede8f7add6db6874a2c294fc993e900) |
| Lei Zhang | 2007-06-21 | [winex11.drv: Reset focus if application does not want to be activated.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e20625e5c95a1852c6ce9e38334f2a187114d602) |
| Nigel Liang | 2007-06-21 | [winex11.drv: Remove call to XCreateFontSet.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2f3a02ea2fd66514c59edd7ed95bb2e0df581350) |
| Evan Stade | 2007-06-21 | [gdiplus: Implemented GdipCreatePath and GdipDeletePath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=14802872b876581fc895f5310e120f83b88b58dd) |
| Dmitry Timoshkov | 2007-06-21 | [shell32: Make SHGetDesktopFolder use a cached instance of IShellFolder.](http://source.winehq.org/git/wine.git?a=commitdiff;h=013652feeef3a69d43cedb7ad431010f1e4dbcdc) |
| Evan Stade | 2007-06-20 | [gdiplus: Implemented GdipDrawArc.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c42f8794a1519ac0dba46c7c638372ba3310b121) |
| Dan Hipschman | 2007-06-20 | [widl: Fix warnings about unused function parameters.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bf5e46a60aa1cfcbb6efd61ebf4d34eb9fb0084d) |
| Evan Stade | 2007-06-20 | [gdiplus: Implemented GdipDrawCurve2.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5c8b83c524c7059edc4b9ef14f88c08f9760506e) |
| Dan Hipschman | 2007-06-20 | [widl: Add tests for arrays of pointers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4e8c8d03e50a13c62711a3afb1bb424a56a9382a) |
| Dan Hipschman | 2007-06-19 | [rpcrt4: Fix typo in union buffer size calculation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d2c15ed01bd0a0766b0b4f6e364a1ad58b333141) |
| Dan Hipschman | 2007-06-19 | [rpcrt4: Remove inaccurate comments.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b09b917a5c2c3f7f615d224500501318b994150b) |
| Evan Stade | 2007-06-19 | [oleaut32: Save load time format of pictures.](http://source.winehq.org/git/wine.git?a=commitdiff;h=72e20d8f57980586dc3745b6fd53e47c84d4faca) |
| Dan Hipschman | 2007-06-19 | [rpcrt4: Fix bug calculating union switch type.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6fd05b1dc7c83743bae5fb1e04941ec3bd560490) |
| Evan Stade | 2007-06-19 | [oleaut32: Added support for decoding some PNG files.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5c5c5aabc549044e1c200e5932b7c5bd835e84be) |
| Dan Hipschman | 2007-06-19 | [rpcrt4: Add encapsulated union tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=08c846a9da942656f2f463154e141e91f03f1112) |
| James Hawkins | 2007-06-18 | [ntoskrnl.exe: Add a stub implementation of KeInitializeTimer.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fbbd91544f2ad1cb179ee6f3cbe124f8a9b79f18) |
| Lei Zhang | 2007-06-18 | [winex11.drv: Send WM\_MOUSEACTIVATE before closing a window.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9a67bded8c5b6ba48470f30437564b3ae1437ef6) |
| James Hawkins | 2007-06-18 | [msi: Properly delete rows from the table, instead of zeroing out the row.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9309f4dfa0f82e3ed2d3582a33fad5eb6a321498) |
| James Hawkins | 2007-06-18 | [msi: Send the expected data to set\_deferred\_action\_props.](http://source.winehq.org/git/wine.git?a=commitdiff;h=82f4e3981bacb58625f1d72893342b8d328365c5) |
| Evan Stade | 2007-06-18 | [gdiplus: Implemented GdipDrawPie/GdipFillPie.](http://source.winehq.org/git/wine.git?a=commitdiff;h=72ab72c50c370372b214bb72814109637db88733) |
| Lei Zhang | 2007-06-18 | [riched20: Add tests for EM\_FORMATRANGE.](http://source.winehq.org/git/wine.git?a=commitdiff;h=55771014e12310ab9c98f9e1bb9e6f0a455fb090) |
| Evan Stade | 2007-06-16 | [gdiplus: Implemented GdipDrawBezier.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8b9f5342b4ba291ab311f7c2b5a4d554083ab900) |
| Lei Zhang | 2007-06-15 | [comctl32: Make modal property sheets modal.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ebb460c3c0c227392699fd1b0809f6f35ea52847) |
| Dan Hipschman | 2007-06-15 | [widl: Handle encapsulated unions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e4679b0c139c83a8e3ceff8033d4442b6f772c3b) |
| Dan Hipschman | 2007-06-15 | [widl: Factor the output functions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e36981e1168e2f4639fd71202a65252dfb1b555e) |
| James Hawkins | 2007-06-15 | [msi: Implement MsiApplyPatchW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d8860d34e4008299320a0cbd0aea033b608a1395) |
| James Hawkins | 2007-06-15 | [msi: Forward MsiApplyPatchA to MsiApplyPatchW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=974e76fe79b54ba98196e637d6d4372f56e50aea) |
| Dan Hipschman | 2007-06-15 | [widl: Handle embedded interface pointers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8709a06028709b11ade91087c1bdba8678adc65c) |
| Dan Hipschman | 2007-06-15 | [widl: Fix a write\_parameters\_init bug.](http://source.winehq.org/git/wine.git?a=commitdiff;h=58dea5c9a833b6587944d36f02a59ff4794fed29) |
| James Hawkins | 2007-06-15 | [msi: Patches are applied based on ProductCode, not ProductID.](http://source.winehq.org/git/wine.git?a=commitdiff;h=261e1179bb2903590794473668dc93ffd3785ff7) |
| Lei Zhang | 2007-06-14 | [comdlg32: Move file dialog resizing code into its own function.](http://source.winehq.org/git/wine.git?a=commitdiff;h=eef9e1ab882fe1f74f84c23b1d4a68b34b65d7fe) |
| Evan Stade | 2007-06-14 | [gdiplus: Brush tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e4fdc9690c6b12e0dc0db4f064100724e378a75e) |
| Lei Zhang | 2007-06-14 | [user32: Remove a unused variable from ES\_PASSWORD test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=dd88237d3ec21ec44bdd500bad02b079c9894943) |
| Evan Stade | 2007-06-14 | [gdiplus: Brush implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cc0a676b22134a68b69f8f268ca308c3920bc0f2) |
| James Hawkins | 2007-06-14 | [msi: Fixed the WriteEnvironmentStrings action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=881f59254a1d2e1fc0b8661c3f0f14d709e80007) |
| Lei Zhang | 2007-06-14 | [user32: Improve cut/copy/paste behavior of password edit boxes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7dd98bb993b886922b07954a3956f32763ea58c1) |
| James Hawkins | 2007-06-14 | [msi: Set the UserSID and ProductCode properties for deferred custom actions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3c444ea350e0688247bd2056b3861dac4af08fbc) |
| Dan Hipschman | 2007-06-13 | [widl: Handle wire\_marshal types.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c0982b42c5293f22b0be0cc3d06e8a2a7ef0e9f9) |
| James Hawkins | 2007-06-13 | [msi: Protect custom actions with a structured exception handler.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9ed5c865e219d4d55ab1da32ccb8f7922343c092) |
| Dan Hipschman | 2007-06-13 | [widl: Handle wire\_marshal pointer attributes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=33250206364dc66451a07abb72f658b84d729ed4) |
| Dan Hipschman | 2007-06-13 | [widl: Test structure argument marshalling.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2bc8808be1f2b4599412321f58311f176101d09b) |
| James Hawkins | 2007-06-12 | [msi: Set the MsiNetAssemblySupport property.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c8a8f77abe87945c48330482c1d94a3d0c527edb) |
| Dan Hipschman | 2007-06-12 | [widl: Simplify correlation descriptor code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=88c812870430b7031c620d91c974dd5e64e8b687) |
| Evan Stade | 2007-06-12 | [gdiplus: Implemented GdipDrawRectangleI.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4b9bfbe7b726981549609fc9d8e7071236b5696a) |
| Evan Stade | 2007-06-12 | [gdiplus: Implemented GdipDrawLineI.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2689b18ea4fcbb3adb65919960aca7b78ab42a8b) |
| Evan Stade | 2007-06-11 | [gdiplus: First pen test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fcd7a62e930f9ed55cbb31a18efd011845c646bc) |
| Evan Stade | 2007-06-11 | [gdiplus: Added first GDI+ graphics implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d50be49775ce850e9f045e9c4272d3e8137e3159) |
| Evan Stade | 2007-06-11 | [gdiplus: First pen implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=63bfd40f6177ca6bd54ac5497f84377e914e818b) |
| Dan Hipschman | 2007-06-08 | [widl: Check for NULL in set\_tfswrite.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b186c4dd0e7bcb92f147fc00e473e495deaef62b) |
| Evan Stade | 2007-06-08 | [gdiplus: Added beginnings of memory and startup functions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a781bbf096d9a3264fe52fa90891b5a19fca9e4d) |
| Dan Hipschman | 2007-06-08 | [widl: Fix incomplete struct/union typedef bug.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4e22899e1316e86e2fc812d2540c7aff04925044) |
| Evan Stade | 2007-06-08 | [gdiplus: Added public headers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=48f10d4bbff73e2d246b3b5c1f7e4d73a40f28ed) |
| Nigel Liang | 2007-06-08 | [shell32: Conformance tests for unicode filenames and fix a bug for file deletion.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1fc0cb75eebeb011a1f620fb96f32245d886916c) |
| James Hawkins | 2007-06-07 | [msi: Add support for large string tables.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a05613a9f29914b0df425d2592f35efd8343b517) |
| James Hawkins | 2007-06-07 | [msi: Represent table data as bytes instead of shorts.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8568e0a4a8f9d6b7cc391fa0041b61389c2d1f45) |
| Lei Zhang | 2007-06-07 | [shell32: Start implementing BIF\_USENEWUI.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7318ae2411eea8e43aa931bbbe676dc2fb7fa233) |
| James Hawkins | 2007-06-07 | [msi: Reduce the amount of code that directly accesses table data.](http://source.winehq.org/git/wine.git?a=commitdiff;h=65f23343ee86fea1f7001684658bf12be1c5a43f) |
| James Hawkins | 2007-06-07 | [msi: Use fetch\_int to reduce code duplication and access to table data.](http://source.winehq.org/git/wine.git?a=commitdiff;h=298699e2426e2e2687d5d655e73ccd9ecd3db2fc) |
| Dan Hipschman | 2007-06-06 | [widl: Replace get\_name with a field reference.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f5baddf88a4061507f470c45c90b2fc374bd5175) |
| Dan Hipschman | 2007-06-06 | [widl: Represent arrays with type\_t.](http://source.winehq.org/git/wine.git?a=commitdiff;h=978b4d4f4e7acb119b1acd59091bfb96bdfd1dd4) |
| Dan Hipschman | 2007-06-06 | [widl: Implement conformant structure handling.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8f689ee023220264790802b625238ce7525b445a) |
| Dan Hipschman | 2007-06-06 | [list.h: Add macros for reverse iteration.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6cf8e6bd77f6d3c98f39740ce9c789762a7eb52c) |
| Lei Zhang | 2007-06-05 | [wined3d: Various spelling fixes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f00670df6135eba1cb162aac954765619ce5f605) |
| James Hawkins | 2007-06-01 | [msi: Implement SummaryInfo::Property get.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f083b3c038eb5b849bfd838a78f32a5f59f0774c) |
| James Hawkins | 2007-06-01 | [msi: Implement Installer::OpenDatabase.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7a289624cfcbc829aabc614093bbd5ae01251529) |
| Dan Hipschman | 2007-05-31 | [rpcrt4: Fix build of test on Solaris by renaming a variable.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e5c8a6eb5d5e278f5997d7082f2f4223fc1d6807) |
| James Hawkins | 2007-05-31 | [msi: Add handling for MsiBreak.](http://source.winehq.org/git/wine.git?a=commitdiff;h=60e95ee6e8ea4a4f43a6c170c917fc7285b76455) |
| James Hawkins | 2007-05-30 | [wintrust: Add stub implementations for CryptCATAdminAddCatalog and CryptCATAdminRelea ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=98350044d5c184445430700c0f916142b693883c) |
| James Hawkins | 2007-05-30 | [msi: Implement the WriteEnvironmentStrings standard action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5b8641a5a43d53f225d6e4c6b1d4ceda90183f3e) |
| James Hawkins | 2007-05-29 | [msi: Perform a forced reboot if a custom action returns ERROR\_INSTALL\_SUSPEND.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c2e91588e9bb470e109e3990799df451b47b0cd6) |
| James Hawkins | 2007-05-29 | [msi: Set the MsiNTProductType property.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b8e0b3c1c82a494baddaeceb55844082eab21ed9) |
| James Hawkins | 2007-05-29 | [msi: Fall back to checking if the cab exists if the volume name doesn't match.](http://source.winehq.org/git/wine.git?a=commitdiff;h=44649d2ff869394c1fa3ef89fdc43395b2214fc7) |
| James Hawkins | 2007-05-29 | [msi: Create the destination directory if it doesn't exist when duplicating files.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1aa0082558050daed4852ad29cc0a12c531a35e6) |
| Evan Stade | 2007-05-25 | [gdiplus: Added stub implementation of gdiplus.dll.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bed761c9e72febb3b2d681fd4e540e149af9e71a) |
| Dan Hipschman | 2007-05-25 | [rpcrt4: Fix test typo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b4e8073f8cceb1a5a1376253e24e6e6347ee16ad) |
| Dan Hipschman | 2007-05-25 | [widl: Shrink type\_t structure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9c30da77ba074d18f2d52891c9bbb32ede6e96a2) |
| Dan Hipschman | 2007-05-25 | [widl: Allow types that reference themselves.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8f7a5d63ec8a96d24c8f56eca7f49b390e1de9af) |
| Dan Hipschman | 2007-05-25 | [widl: Handle pointers in unions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=00ce411231b4dd94fef20e98b1a9c08c3321670e) |
| James Hawkins | 2007-05-24 | [msxml3: Add initial implementation of IXMLDocument.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f5e9a1ea6f6eb7e750ff09060937ea91012b8985) |
| James Hawkins | 2007-05-24 | [msi: Remove a misleading ERR, as this fails if a file doesn't exist, which is common.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f5c2806ca19bfcfe1c7d3002714b4df829a9d650) |
| James Hawkins | 2007-05-24 | [msi: Add the ability to deformat the component's source.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ea2c96c5dfb42a5efceeaf6d044953b93a2de5f3) |
| James Hawkins | 2007-05-24 | [msxml3: Add tests for IXMLDocument.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e24667cc6e5f5dd1e3434d9073496970130de4e0) |
| James Hawkins | 2007-05-24 | [msxml3: Add tests for IXMLElement and IXMLElementCollection.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9c04d0d8ca8811f5ddfc66c987c83a50075a1da9) |
| James Hawkins | 2007-05-24 | [msxml3: Add initial implementation of IXMLElement and IXMLElementCollection.](http://source.winehq.org/git/wine.git?a=commitdiff;h=74f18d968ffb75a307932879810ecf87b4c9f915) |
| Nigel Liang | 2007-05-22 | [shlwapi: Stub implementation for SHSetTimerQueueTimer.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ddbb317915f7cfb1dd6f48431f4fde43527eb068) |
| Lei Zhang | 2007-05-22 | [include: Add missing definitions to shlobj.h.](http://source.winehq.org/git/wine.git?a=commitdiff;h=00bc8fa184f2df997ffab28e307b9ddbd6e94181) |
| Dan Hipschman | 2007-05-18 | [widl: Lay framework for unions with simple unions working.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c5aaadc4c89a49696dc265cb1498e2e28837534a) |
| Dan Hipschman | 2007-05-18 | [widl: Replace erroneously removed current\_func assignment.](http://source.winehq.org/git/wine.git?a=commitdiff;h=18724eaeb8534a04f9d530692f2bee42cb87f58b) |
| Dan Hipschman | 2007-05-16 | [widl: Write some structures to the type format string on the fly.](http://source.winehq.org/git/wine.git?a=commitdiff;h=52ca3ebadac7eb1132fce34e750d4d96b48e052c) |
| Dan Hipschman | 2007-05-16 | [widl: Improve handling of offsets in the type format string.](http://source.winehq.org/git/wine.git?a=commitdiff;h=217fc9c0f3d5d514eb0a2cf352783374855ce17c) |
| Dan Hipschman | 2007-05-12 | [widl: Remove an unnecessary assignment in write\_pointers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=faf50715493df83b38e43176cb2d13c4149a0ed9) |
| Dan Hipschman | 2007-05-12 | [widl: Handle pointers fields that point to structures.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d9c120490fbea62f5696ed99c7f4d8390f9dfef4) |
| Jacek Caban | 2007-05-11 | [mshtml: Split code from OnDataAvailable.](http://source.winehq.org/git/wine.git?a=commitdiff;h=98da8e2823f4ab5aff8bb25a5fe80995fcd8e935) |
| Jacek Caban | 2007-05-11 | [mshtml: Don't crash in OnStopBinding if This-&gt;binding is null.](http://source.winehq.org/git/wine.git?a=commitdiff;h=94a264d0beef21f51655e3cacebc699e74ee4d7b) |
| Jacek Caban | 2007-05-11 | [mshtml: Added IPersistStreamInit::Load implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=920f628c6e6934131608db98388ad4f06ac8b862) |
| Jacek Caban | 2007-05-11 | [mshtml: Added IPersistStreamInit::Load test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=66067781d6e5df7499abe419216172e630383056) |
| Jacek Caban | 2007-05-11 | [mshtml: Move AddRequest call to the separated function.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2dd9fad610ea4197c3b71352c9cdaa5db4d8daac) |
| Jacek Caban | 2007-05-11 | [mshtml: Split IPersistMoniker::Load.](http://source.winehq.org/git/wine.git?a=commitdiff;h=09adb8cf051ac76df81260afd68a99974c2bbd6c) |
| Dan Hipschman | 2007-05-10 | [widl: Remove var\_t's ptr\_level field and start write\_pointers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ef433e279295beeadcbec3f36016ffc3587834a3) |
| Dan Hipschman | 2007-05-10 | [widl: Remove redundant get\_var\_vt function.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e7495555a09e1c5631d7de77926a95bf3f551201) |
| Dan Hipschman | 2007-05-10 | [widl: Add string\_of\_type function, prettify code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=933ca7b126c12c222a7c5509c266f96af8221b9a) |
| James Hawkins | 2007-05-10 | [msi: Only check the volume label for every media after the first disk.](http://source.winehq.org/git/wine.git?a=commitdiff;h=666cfd1c0346904dc5d3c27eee80ce871bec26ca) |
| Dan Hipschman | 2007-05-10 | [widl: Simplify make\_safearray.](http://source.winehq.org/git/wine.git?a=commitdiff;h=541dddfde37120d1334dade507e390836403bf82) |
| Dan Hipschman | 2007-05-10 | [widl: Remove dead code in write\_msft.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=234855f059a374c76783c180dd00193023da6aff) |
| James Hawkins | 2007-05-10 | [msi: Deformat the key path before opening the key.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0de574b258b86c1399af5a53485280e4eb8b7952) |
| James Hawkins | 2007-05-09 | [msi: Check the volume name when changing media.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6eb7eadffa5e9863722058325c0977142cd9af49) |
| James Hawkins | 2007-05-09 | [msiexec: /quiet is the same options as /qn.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5b8bad751894a523d75865d4bc2be7264cd2c924) |
| James Hawkins | 2007-05-07 | [msi: Remove debugging printf statements.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e962b0a7df3bc4405d1c94b0b0054f4e6cdb60e3) |
| James Hawkins | 2007-05-07 | [msi: Add stub handlers for the remaing standard actions that reference tables.](http://source.winehq.org/git/wine.git?a=commitdiff;h=987c2c85e136f077e52390acf04ef09fdb80cade) |
| James Hawkins | 2007-05-07 | [msi: Set the text limit of the edit control if the limit is given.](http://source.winehq.org/git/wine.git?a=commitdiff;h=933fd8b8797b340558e06b5d19e51d94b068c5ab) |
| James Hawkins | 2007-05-07 | [msi: Add the ES\_AUTOHSCROLL style to the edit control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7fe3ba934cb0f4908d20a9136b36f206c1b78fa6) |
| James Hawkins | 2007-05-07 | [msi: Only allow valid styles in msi\_dialog\_get\_style.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7f4a4e161f561a8e7416e918c4e57affee688193) |
| James Hawkins | 2007-05-07 | [msi: Add handling for the ReinstallMode control event.](http://source.winehq.org/git/wine.git?a=commitdiff;h=770e49cd3c67851c3c6fc0222cd220d6b2e21015) |
| James Hawkins | 2007-05-07 | [msi: Remove incorrect ERR as messages can be sent before the control is created.](http://source.winehq.org/git/wine.git?a=commitdiff;h=12c33ab8aa0d314c21afbfc850f94201faa58cf9) |
| James Hawkins | 2007-05-01 | [msi: Add tests that show that costing is run in both the UI and Execute sequences.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d8586e164f7892c480db3a1427b4ec6a6be98c05) |
| Dan Hipschman | 2007-05-01 | [widl: Get rid of the tname field of var\_t, simplify code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d676d3be5fce72d35cb9eb7063ace424f3bcf78e) |
| James Hawkins | 2007-05-01 | [msi: Reset the folder's resolved target before setting the target in CostFinalize.](http://source.winehq.org/git/wine.git?a=commitdiff;h=baad888766850ad390079a3abdf561517b61ef33) |
| Dan Hipschman | 2007-05-01 | [widl: Get rid of the typeref\_t structure, simplify code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1ecbb01617909b0ed149448afc5c8c81e75acb3b) |
| James Hawkins | 2007-05-01 | [msi: Run the costing actions for both the UI and execute sequences.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1104dc088df7f0f492c1bc6b48258d8a2ce9a956) |
| Dan Kegel | 2007-04-28 | [advapi: Improve SetEntriesInAclA stub.](http://source.winehq.org/git/wine.git?a=commitdiff;h=67e2c97a88ce75dbbe22eefcd3137bf8315786e2) |
| Dan Hipschman | 2007-04-26 | [rpcrt4: Add a testcase for RPCs with fixed-size arrays.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ba17c25e62970340a67d0e15d818694d87143fcb) |
| James Hawkins | 2007-04-25 | [msi: Implement special handling for the \_Streams table.](http://source.winehq.org/git/wine.git?a=commitdiff;h=da55285acba1839fca9cf93422a42eac062760ed) |
| Lei Zhang | 2007-04-23 | [comdlg32: Initialize CommDlgExtendedError() return value for file dialogs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7aa1b2e419976a14495227bfd45b37cdae219207) |
| James Hawkins | 2007-04-21 | [msi: Return MSICONDITION\_NONE in MsiDatabaseIsTablePersistent if the table doesn't ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=d677bd7f3b43cd94fcf95bfed035b4e817fffd34) |
| James Hawkins | 2007-04-21 | [msi: Add the \_Property table back, with tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b4bb6e5b5d5b85f0bc4bbbad2b6a8ec3872a5759) |
| James Hawkins | 2007-04-21 | [msi: Abstract MSI\_RecordSetStream.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7d3162e6bed476c937a8d2f3d1b44c8076959e61) |
| James Hawkins | 2007-04-21 | [msi: Add an internal MSI\_ViewModify.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2b4bf44b793fa1dcf102289b2c789a3284669f07) |
| Lei Zhang | 2007-04-20 | [wineshelllink: Fall back to $HOME if $HOME/Desktop does not exist.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d0c83654f8a9928be13539714c723d2ec9cfe0a5) |
| James Hawkins | 2007-04-15 | [msi: Add handling for the concurrent install custom action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=98eafa870c619dbf78ae28feb8f5abc904de5cb9) |
| James Hawkins | 2007-04-15 | [msi: Run the InstallExecute sequence if the InstallUISequnce table is empty.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6da8041d4752e86d65d46348f84810bcd99c823a) |
| James Hawkins | 2007-04-15 | [msi: Add tests for the concurrent installation custom action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4cc48b7710eead6051652eb646c44d82f741bcab) |
| James Hawkins | 2007-04-15 | [msi: Generalize the msi\_custom\_action\_info struct so other custom actions can use it.](http://source.winehq.org/git/wine.git?a=commitdiff;h=06df9f790d175432be7352ae555bb441c21a351e) |
| Lei Zhang | 2007-04-13 | [comctl32: monthcal: GetMonthRange Tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bf7b0b89fedd4ac3b9adfa143e6f05638cfb6838) |
| Lei Zhang | 2007-04-12 | [user32: WM\_ACTIVATEAPP on minimize message test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c569ab2a6727ce7cef6ca6e90f398c50640493bc) |
| Dan Kegel | 2007-04-12 | [winex11.drv: GetAsyncKeyState must check mouse buttons, too.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c2ae970e6055f6d18a9166c4cd2d760edfabf20d) |
| Lei Zhang | 2007-04-12 | [comctl32: More monthcal hit tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b47a756ac7d7d1b158c2f37006c7e60fc1db37ab) |
| James Hawkins | 2007-04-11 | [msi: Reset the is\_extracted flag when every cabinet is loaded.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7ef8428b5e5e14c5a048d7a655b68249178837c1) |
| Lei Zhang | 2007-04-10 | [comctl32: Fix first day of the week in monthcal.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6fb16fca6beeaf80c1c0294ebeff88da13e28950) |
| Lei Zhang | 2007-04-06 | [advapi32: Spelling fixes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d347ebe1968a32d62834d897ecfed647e001c06a) |
| Dan Kegel | 2007-03-31 | [imagehlp: BindImageEx stub should report success.](http://source.winehq.org/git/wine.git?a=commitdiff;h=71971409c8489b1c52dda8ac3a2d46788a18d9b9) |
| James Hawkins | 2007-03-29 | [msi: Load the folder property if available and requested.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8cedb218c314f444612fd3dea67a8834d2f596e9) |
| James Hawkins | 2007-03-28 | [setupapi: The Inf file should be copied regardless of the destination buffer, with ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=ff326fd0ffd4ad017634d6d068781d8a0736d4a2) |
| James Hawkins | 2007-03-28 | [setupapi: Don't allow relative paths in SetupCopyOEMInf.](http://source.winehq.org/git/wine.git?a=commitdiff;h=efa6591fff772c7fc88f3dd26500610f55d6b551) |
| James Hawkins | 2007-03-28 | [setupapi: Correct the Inf output position.](http://source.winehq.org/git/wine.git?a=commitdiff;h=672952d2b6abf525d3ccd73b68ee418f51f8eae2) |
| James Hawkins | 2007-03-28 | [setupapi: SetLastError to ERROR\_SUCCESS on success.](http://source.winehq.org/git/wine.git?a=commitdiff;h=405b96e979dcb751988e061cd1f78319232d3d84) |
| James Hawkins | 2007-03-28 | [setupapi: Handle the SP\_COPY\_NOOVERWRITE flag.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3e5f62b2d8d7353f890ca6e4fb27809c9f7dae8f) |
| Jacek Caban | 2007-03-28 | [mshtml: Added DispHTMLDocument dispinterface declaration.](http://source.winehq.org/git/wine.git?a=commitdiff;h=394c3f9adbc9952e1deb3932cab36cc1e0f63f0e) |
| Jacek Caban | 2007-03-28 | [mshtml: Added DIID\_DispHTMLDocument to QueryInterface.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0b94f19cb93dd2728b81a055f4a168edd96eaf9a) |
| Jacek Caban | 2007-03-28 | [winnt.h: Added activation context structures declarations.](http://source.winehq.org/git/wine.git?a=commitdiff;h=06bd1bf8e1620da270a90e1c7640634397506704) |
| James Hawkins | 2007-03-26 | [setupapi: Add missing SetupCopyOEMInf flags.](http://source.winehq.org/git/wine.git?a=commitdiff;h=da85c0905d26ddc31a8deb7b426b41e75fac2b44) |
| James Hawkins | 2007-03-26 | [setupapi: Add several tests for SetupCopyOEMInf, with fixes so the tests don't crash.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9eaea34e041671fa63095a825c32978d1a9780d5) |
| Jacek Caban | 2007-03-19 | [spoolsv: Added spoolsv.exe.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d1ddc9c1f72e796fba3997c07dc04a1d822a6e29) |
| Jacek Caban | 2007-03-19 | [spoolss: Added RevertToPrinterSelf stub implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c88ccdc1ef9c63a416024461a92d6e5bb98db347) |
| Jacek Caban | 2007-03-19 | [wine.inf: Register Spooler service.](http://source.winehq.org/git/wine.git?a=commitdiff;h=546de27f1124b974bd777ec833964ae7731f736d) |
| Jacek Caban | 2007-03-19 | [advapi: Improve SetEntriesInAclW stub.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2cd033eee1a2f442d40a4c1663d500ac7e5ef9c0) |
| Jacek Caban | 2007-03-19 | [advapi: Constify argument of StartServiceCtrlDispatcher[AW](http://source.winehq.org/git/wine.git?a=commitdiff;h=112257e59db7cc8c60a151b190f5cc4c074ed46d) functions.] |
| Dan Kegel | 2007-03-12 | [advapi32: RegGetKeySecurity needs to pass length of struct to caller.](http://source.winehq.org/git/wine.git?a=commitdiff;h=60cb73b573d139f49b4445318ce3762685a9ff87) |
| Lei Zhang | 2007-03-02 | [regedit: Correctly parse key name containing '](http://source.winehq.org/git/wine.git?a=commitdiff;h=4de636208f503cce544cebd2564143635b41c462)' when deleting/exporting.] |
| Lei Zhang | 2007-03-02 | [regedit: Allow entering - for a key in a .reg file to delete that key.](http://source.winehq.org/git/wine.git?a=commitdiff;h=054fd8cb42fb3b3b13fee48a7747f0063d853f09) |
| Lei Zhang | 2007-03-01 | [regedit: Correctly parse key name containing '](http://source.winehq.org/git/wine.git?a=commitdiff;h=d113419682a1a723336dafa53f2d81c223fad395)'.] |
| Lei Zhang | 2007-03-01 | [regedit: Updated English resources to remove shortcut conflicts.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8f05d80aa966ad40db6aab37dc26527d8c8cd7fd) |
| Lei Zhang | 2007-03-01 | [regedit: Removed dead code from regproc.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1a54a89b8bc4ce4d3cb09bae846f8ac5903f552d) |
| James Hawkins | 2007-02-28 | [comctl32: Add message ids to allow multi-window test sequences.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2b5f79c9a851961024a2dbffbf2160f698baa6b3) |
| James Hawkins | 2007-02-26 | [msi: Overwrite an existing read-only file when copying the install file.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ba40c463d76235474249b92654d3f9caee5778b7) |
| James Hawkins | 2007-02-25 | [msi: Check for a NULL text entry, as it can be blank in the VolumeCostList control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d4a324940b3b92595dd26a92561cc80b01b0a3bd) |
| James Hawkins | 2007-02-25 | [msi: Add tests for using markers in SELECT clauses.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a40d687133b962128ed61ef0264dc3e14f861491) |
| James Hawkins | 2007-02-25 | [msi: Free the custom action data after the thread function executes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=747f19f01196cba5a24a1f60a306f815ef4763b0) |
| James Hawkins | 2007-02-20 | [msi: Cleanup the dialog event subscriptions when destroying the dialog.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0746b9076d2c32906de4d291e1ce8f809927988c) |
| Lei Zhang | 2007-02-17 | [comctl32: Move up-down msg seq test functions into msg.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b29c99c59a59d9aff82518a108de61f088cb1b34) |
| Lei Zhang | 2007-02-13 | [tools/wineshelllink: Create links with WINEPREFIX.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9a3a144896e2acf6c40e8e90a17b3478622d8450) |
| James Hawkins | 2007-02-08 | [msi: Don't skip files continued from a previous cabinet.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5b8282120a676e66a0e767438cb8abfe43bddd58) |
| James Hawkins | 2007-02-04 | [msi: Allow uncompressed files before compressed files in the same media.](http://source.winehq.org/git/wine.git?a=commitdiff;h=30577c253a7095184e00a4881c7d05d8a4cb5636) |
| Dmitry Timoshkov | 2007-01-23 | [user32: Using DIB APIs to convert a DDB to monochrome is wrong, do it differently.](http://source.winehq.org/git/wine.git?a=commitdiff;h=81a294f76d47fcacdfff185617f27c6872d578fd) |
| Dmitry Timoshkov | 2007-01-23 | [user32: Do not use DIB APIs for bitmap bits in a device dependent format.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7670d76690f12a240ec0241a4bd96b8f5f5a7c6a) |
| Dmitry Timoshkov | 2007-01-22 | [gdi32: Add a GetDIBits test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f31b67ae441b87028a236898572efbe359d16b88) |
| Lei Zhang | 2007-01-22 | [comctl32: Fix the updown control test to use the optional flag.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4de56b1b4dc3a741f68f49efd19d157b1084f6c0) |
| Dmitry Timoshkov | 2007-01-22 | [gdi32: Add a simple SelectObject test for bitmaps.](http://source.winehq.org/git/wine.git?a=commitdiff;h=295f8101ec882bd62042ff4526f0cb3f6c2cf5bf) |
| Dmitry Timoshkov | 2007-01-18 | [user32: Some apps pass a color bitmap as a mask to CreateIconIndirect, convert it ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=64f1d97a5435df2f8275c304145635bce290db14) |
| James Hawkins | 2007-01-16 | [oleaut32: Initialize nrofnames to keep from freeing unused memory in the error case.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c8eb80763956d5b618d5f5ab30ddabb72d81a736) |
| James Hawkins | 2007-01-16 | [advapi32: Add tests for RegQueryValue.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6cc4510b719a0014afe948c59fb274c362a45b70) |
| James Hawkins | 2007-01-11 | [mshtml: Use the correct variable in the FIXME.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d06ff0ea6909fa2ba12bf296565191e857384fb4) |
| James Hawkins | 2007-01-11 | [winedbg: Check buffer for NULL before writing to it.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8be71fef5ba74034170259e40a2ec3cec5ac0942) |
| James Hawkins | 2007-01-11 | [winspool.drv: Check for get\_filename failure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=68406933714001224b367d4d6f40f563c00fd092) |
| James Hawkins | 2007-01-10 | [advpack: Fill the output buffer to workaround a bug in IE7s advpack.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b3331d1a76a5116b391b0757bfcf6752a307d3d3) |
| James Hawkins | 2007-01-10 | [comctl32: Rewrite the up-down control tests to add message checking.](http://source.winehq.org/git/wine.git?a=commitdiff;h=74ada83c60fd153bbcb45fe41deda326b79f4816) |
| Lei Zhang | 2007-01-03 | [comctl32: Add initial tests for the status bar control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3a463f039b544ad27ae3b8e8945aacc598f3e8b0) |
| James Hawkins | 2006-12-05 | [msi: Initialize sid\_str to NULL.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0b652fe8c65d056ed761b59f9e79c848b44a704d) |
| James Hawkins | 2006-12-05 | [msi: Fail if stg is NULL.](http://source.winehq.org/git/wine.git?a=commitdiff;h=00fa70dbc1cdced835f559a847f8dd325334a25d) |
| James Hawkins | 2006-12-01 | [msi: Set the UserSID property.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8ae81d0620a0c11febea41fdfd463f692e506dbc) |
| James Hawkins | 2006-12-01 | [msi: Add handling for the StartServices action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=58bb3571defcde50770dc214608b890ab932b8f7) |
| James Hawkins | 2006-12-01 | [shell32: Move a NULL pointer check before the place where we dereference the pointer.](http://source.winehq.org/git/wine.git?a=commitdiff;h=44b0b462cbbc118ce4b372dfecfb4f5f902b4e03) |
| James Hawkins | 2006-11-30 | [msi: Use mi-&gt;source if the source is not a full path.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a64945baeab3f6ccf41494dba078b16c92fde3bc) |
| James Hawkins | 2006-11-30 | [advapi32: Add tests for LookupAccountName.](http://source.winehq.org/git/wine.git?a=commitdiff;h=19a49eb51afbe860ca2614c58589f6f915124ddd) |
| James Hawkins | 2006-11-30 | [advapi32: Remove redundant NULL checks before CRYPT\_Free.](http://source.winehq.org/git/wine.git?a=commitdiff;h=024237efaaaa689d077b299016e0dedea541b722) |
| James Hawkins | 2006-11-28 | [msi: Add handling for the InstallODBC action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d3bec325007ea60ae041ed17d750162e0cdb2f91) |
| James Hawkins | 2006-11-28 | [msi: Don't fail if we can't remove an existing install file.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7125d3073d297f1b9a53d60958012ec59e3ca475) |
| James Hawkins | 2006-11-18 | [kernel32: Replace magic numbers with descriptive defines.](http://source.winehq.org/git/wine.git?a=commitdiff;h=15fd7a028fb277514db870c62cc1a8b9b2ad5432) |
| James Hawkins | 2006-11-13 | [msi: Notify the external UI handler when changing media.](http://source.winehq.org/git/wine.git?a=commitdiff;h=31a9b087c15b7798d7c5b7766f151522add47028) |
| James Hawkins | 2006-11-10 | [msi: Fix a heap corruption bug by resizing the src string before adding to it.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5cc4a8915f5b9873c16a2c2b6465d795fb05d019) |
| James Hawkins | 2006-11-08 | [msi: Add support for continuous cabinets.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fa8fc1628a455928f36e5dc884f87ad22a717fb4) |
| James Hawkins | 2006-11-08 | [msi: Move the file sequence check out of ready\_media\_info to avoid an unnecessary ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=d21e1cc05bfbedc651b9c188f854fdb595f6ef1d) |
| James Hawkins | 2006-11-08 | [msi: Use disk\_prompt from the media\_info structure instead of passing an extra parame ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=a621c2a6619ec43a1b33c4464e13864739c366cb) |
| James Hawkins | 2006-11-08 | [msi: Only add text to the scroll control if text is provided.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9d899129bf696afabf76ef5ba6f24fcf582abff7) |
| James Hawkins | 2006-11-08 | [msi: Factor out load\_media\_info from ready\_media\_for\_file.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6ef6512938d1162114735a482572755f9dd4d099) |
| James Hawkins | 2006-11-08 | [msi: Extract cabinets in ACTION\_InstallFiles. ready\_media is for finding and loading ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=6d537a311fb44edcdbca170ffab31ead2df73ebd) |
| James Hawkins | 2006-11-07 | [msi: Model the media\_info structure members after the columns in the media table.](http://source.winehq.org/git/wine.git?a=commitdiff;h=de3b84df091ab13a6685f34fb905b38260e4b1d3) |
| James Hawkins | 2006-11-07 | [msi: Use the media\_info structure instead of passing in individual values to extract ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=b81f1ce561f31bf6ae729ba052e3b29508ae3924) |
| James Hawkins | 2006-11-07 | [msi: Store the base URL of the MSI package if it is downloaded.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ae18c2dc7f7e337b0eb7f3a15f04d35a56355586) |
| James Hawkins | 2006-11-07 | [msi: Factor schedule\_install\_files out of ACTION\_InstallFiles.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a13bbaf7361830638c9e34c8a57bb2d955dae966) |
| James Hawkins | 2006-11-07 | [msi: Use the file's component instead of passing an extra parameter to set\_file\_source.](http://source.winehq.org/git/wine.git?a=commitdiff;h=988509e1afe1a1993c6c2fc336cff3dde3a06e38) |
| James Hawkins | 2006-11-07 | [msi: Add more tests for installing from cabinets.](http://source.winehq.org/git/wine.git?a=commitdiff;h=84f34ec2101106320263c8df6229c7cccf7a66f0) |
| James Hawkins | 2006-11-07 | [msi: Use msi\_alloc\_zero instead of a helper function that sets everything to zero.](http://source.winehq.org/git/wine.git?a=commitdiff;h=842ffc35456fa447a9653b60938d68e845cc444b) |
| James Hawkins | 2006-11-07 | [msi: Factor copy\_install\_file out of ACTION\_InstallFiles.](http://source.winehq.org/git/wine.git?a=commitdiff;h=542101fcda71016022fca5a8040acefec7878f01) |
| James Hawkins | 2006-11-07 | [msi: Factor out download\_remote\_cabinet and reuse extract\_cabinet\_file to extract ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=1ae4ab6ef7b911199c65dabd10be49657aeccb42) |
| James Hawkins | 2006-11-01 | [advpack: Use the full path of the INF file as the source directory if the CAB file ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=a27ae7929566f42ee3dd420af7f284b57510d98b) |
| James Hawkins | 2006-10-27 | [msi: Implement handling for the ErrorDialog and use it to change media.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c6bfbde849b5ddf2217f30bbac31bc7e43043278) |
| James Hawkins | 2006-10-27 | [msi: Extract cabinets based on DiskId, not LastSequence.](http://source.winehq.org/git/wine.git?a=commitdiff;h=62dc9ca691ea1449dc217351dc6ea7f9ca33ce17) |
| James Hawkins | 2006-10-27 | [msi: Test the order in which cab files are handled in the Media table.](http://source.winehq.org/git/wine.git?a=commitdiff;h=005c0a792ea48a1e95b321d9a2a3c70c1973959d) |
| James Hawkins | 2006-10-26 | [msi: Add tests for the UPDATE sql command.](http://source.winehq.org/git/wine.git?a=commitdiff;h=62aedea856037208e93e36dcc5b7e6cc737b62e8) |
| James Hawkins | 2006-10-24 | [msi: Remove two unnecessary install tables.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a93763ae21ae73dd9bf252d769a8ce31ccd02833) |
| James Hawkins | 2006-10-24 | [msi: Remove unused function pointer and definitions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a3a3d6c2547b36892f7dbc9ffe7a2806b87edb0e) |
| James Hawkins | 2006-10-24 | [advpack: Fix the full path check.](http://source.winehq.org/git/wine.git?a=commitdiff;h=615d09f285015e392c66c5873e97c871323f9144) |
| James Hawkins | 2006-10-24 | [msi: Add support for localizable strings in MsiDatabaseImport.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5b19cc79bd4c35f1710280e569ec2847597b679c) |
| James Hawkins | 2006-10-24 | [msi: Allow more customization of install test files.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3fc13d4b051bd7189e8d8af85996dad755759566) |
| James Hawkins | 2006-10-24 | [msi: Add tests for installing from continuous cabinets.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1f3f88bf67d32983ff00d96bf58bf91c6e72ae02) |
| James Hawkins | 2006-10-20 | [msi: Add tests for integer column types.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fcd57a3fc4e8a2a0664ba280a4fc570009aa30ee) |
| James Hawkins | 2006-10-20 | [msi: Allow more than one primary key in a table when importing a database.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a66584e1a26b4bc12ec0ae1befa87fdd67aa0b84) |
| James Hawkins | 2006-10-20 | [msi: Integer columns can have the 'NOT NULL' modifier too.](http://source.winehq.org/git/wine.git?a=commitdiff;h=279f8158f8b96e992f18441822cbce24df855760) |
| James Hawkins | 2006-10-19 | [msi: Implement the InstallServices action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9bc12ade13d6ac69ecce7a40e5682516a36c2f1b) |
| James Hawkins | 2006-10-19 | [msi: Only initialize a component's state if it is linked with a feature.](http://source.winehq.org/git/wine.git?a=commitdiff;h=929395c0f0b7dbd1978adfea5079445228b6b7e8) |
| James Hawkins | 2006-10-19 | [msi: Use the ProgramFileDir reg value instead of ProgramFilesPath.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7330a03200d7b91150a21ed6bdf41c64548cf2bd) |
| James Hawkins | 2006-10-18 | [msi: Add tests for the InstallServices action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d6632dd0fbcdcfc9e8b36d3e2dc048ae3c37cfa2) |
| James Hawkins | 2006-10-18 | [msi: Run SetProperty events before all other events no matter what the order is.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8321276cd34486bc6bf1e07c0e99c73423288854) |
| James Hawkins | 2006-10-18 | [tools/wine.inf: Add the ProgramFilesPath registry entry.](http://source.winehq.org/git/wine.git?a=commitdiff;h=463cec6af69a07adb59de376427bbb2079099293) |
| James Hawkins | 2006-10-18 | [msi: Set the USERNAME and COMPANYNAME properties when initializing a package.](http://source.winehq.org/git/wine.git?a=commitdiff;h=08831b4a1e38afa8a5f56da6deef1527df4bbb50) |
| James Hawkins | 2006-10-16 | [msi: Revert &quot;msi: Perform button control events in greatest to least order.&quot;](http://source.winehq.org/git/wine.git?a=commitdiff;h=9119b700ed241391b6c52aecb697713bce529eee) |
| James Hawkins | 2006-10-13 | [mscoree: Add stub implementations of CorBindToRuntimeHost and GetCORVersion.](http://source.winehq.org/git/wine.git?a=commitdiff;h=eb676fff06ef702c6033f65edb7d39ebe31040ea) |
| James Hawkins | 2006-10-13 | [mscoree: Add missing stubs to the spec file.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b2f21fa0710dd6771e2ee6886bd1172dfcb9ab50) |
| James Hawkins | 2006-10-13 | [clusapi: Add the clusapi.h public header.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3cb50048760afefc61d8dcb6df599a857bb069c4) |
| James Hawkins | 2006-10-13 | [include: Move cfgmgr32.h to include/ to match the SDK.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3b6017ae1894648f478ab242207e1153c20c8b57) |
| James Hawkins | 2006-10-13 | [msi: Also set the SOURCEDIR property in MSI\_InstallPackage.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3797e6cadaf9fa1cb8e0995a06c79d71e217d35f) |
| James Hawkins | 2006-10-11 | [cabinet: Make internal functions static.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e981278769600d3993ef029603d18d0d9d2c095d) |
| James Hawkins | 2006-10-11 | [crypt32: Make an internal function static.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d813d8db1b144266cc6a5b247353c074af0f2644) |
| James Hawkins | 2006-10-11 | [advapi32: Add missing declarations to the public headers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cdd717bc1bc0a85b204d880400b37675238877c4) |
| James Hawkins | 2006-10-11 | [comctl32: Make internal functions static.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cd073a66a5ef6904acd0bec4ad43024ecd1655e6) |
| James Hawkins | 2006-10-11 | [gphoto2.ds: Make an internal function static.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c9384a20329767b4aaface9c37943e8a71a83802) |
| James Hawkins | 2006-10-11 | [advapi32: Make internal functions static.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2730fe6d1cdcf91ea5910ef8663d9093b892983a) |
| James Hawkins | 2006-10-10 | [msi: Set the SourceDir and SOURCEDIR properties in the ResolveSource action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c507543554b519f0dc3c50756c7c207f0c9e988a) |
| James Hawkins | 2006-10-10 | [msi: Clean up after the package tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=58870ce841f71d162277360930e82841a1729069) |
| James Hawkins | 2006-10-09 | [msi: NULL-terminate dst on error.](http://source.winehq.org/git/wine.git?a=commitdiff;h=915898fbb75b8f2f945f4934d3b67496d3073558) |
| James Hawkins | 2006-10-09 | [advpack: Make internal functions static.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8b9ad4d3bc04f126e40e679dcf3d58b3e35dcc05) |
| James Hawkins | 2006-10-09 | [msi: Add missing declarations to the public headers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5fd3c4ad15bfe7f976ca421c81f285487ddced29) |
| James Hawkins | 2006-10-09 | [msi: Make internal functions static.](http://source.winehq.org/git/wine.git?a=commitdiff;h=563a50ab357049b15a84951397699f783e907711) |
| James Hawkins | 2006-10-09 | [msi: Add missing sizeof(WCHAR) multiplier.](http://source.winehq.org/git/wine.git?a=commitdiff;h=42b05ea311514414198293b609b96435877739ba) |
| James Hawkins | 2006-10-07 | [msi: Perform button control events in greatest to least order.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f721a24a13bf250f0794b7249ffa863619b0b450) |
| James Hawkins | 2006-10-07 | [shdocvw: Return S\_OK in PersistStorage\_InitNew.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e55ed113faee6c3d52cdd5043069f041c34c7bc0) |
| James Hawkins | 2006-10-07 | [janitorial: Remove redundant NULL checks before CoTaskMemFree (found by Smatch).](http://source.winehq.org/git/wine.git?a=commitdiff;h=99e2c6dff20f1692d70073b38e8fad43722269ed) |
| James Hawkins | 2006-10-07 | [janitorial: Remove redundant NULL checks before SHFree.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7b89ff88e85a95f1e16420d25654887c71adcc6b) |
| James Hawkins | 2006-10-07 | [advpack: Win64 printf format warning fixes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=29a55bd512267af743a2ccbc8833750d03678c42) |
| James Hawkins | 2006-10-06 | [advapi32: Remove redundant NULL check before SERV\_free (found by Smatch).](http://source.winehq.org/git/wine.git?a=commitdiff;h=ca118989f454554f6913337cca272a925653d0db) |
| James Hawkins | 2006-10-06 | [crypt32: Remove redundant NULL checks before CryptMemFree (found by Smatch).](http://source.winehq.org/git/wine.git?a=commitdiff;h=b96ac007645c94c8f44ec8983f53c5b4a247cb43) |
| James Hawkins | 2006-10-06 | [msi: Make msi\_dialog\_dup\_property return a copy of the property if the property is ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=9024a88dd996887a34d10b39231971b22f703143) |
| James Hawkins | 2006-10-06 | [dinput: Call missing LeaveCriticalSection in the error case (found by Smatch).](http://source.winehq.org/git/wine.git?a=commitdiff;h=553bafd535c2dbbc5f2a49b423982285c35112e1) |
| James Hawkins | 2006-10-06 | [dbghelp: Remove redundant NULL checks before pdb\_free (found by Smatch).](http://source.winehq.org/git/wine.git?a=commitdiff;h=1b95f6093868254b612138ae1136d2257a551b0f) |
| James Hawkins | 2006-10-06 | [ddraw: Set lplpDirect3DViewport3 to NULL before returning an error (found by Smatch).](http://source.winehq.org/git/wine.git?a=commitdiff;h=1a922b6a3887d89a767af46aef94d7d10acb4ed2) |
| James Hawkins | 2006-10-04 | [msi: Only apply the last font style in the list of styles.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f16ddf1b325b2e2b57b4bd940b7372135b968d00) |
| James Hawkins | 2006-10-04 | [user: Add missing sizeof(WCHAR) multiplier.](http://source.winehq.org/git/wine.git?a=commitdiff;h=96963d2bc18aa8fc46aad623c6c122cfa8e4054c) |
| James Hawkins | 2006-10-03 | [msi: Assign the property to path if the property is empty.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e3496be256a563c97e91871ef21f149bae4d63be) |
| James Hawkins | 2006-10-03 | [msi: Properly initialize the SelectionTree control's attributes and property values.](http://source.winehq.org/git/wine.git?a=commitdiff;h=de0efba366ede0f1f3cd62fc114aefe51ebe05fc) |
| James Hawkins | 2006-10-03 | [msi: Publish the SelectionPath event in the SetTargetPath event.](http://source.winehq.org/git/wine.git?a=commitdiff;h=aea0dcc86da5c4779c04c87e4db7c9d409c7d739) |
| James Hawkins | 2006-10-03 | [msi: Handle the SelectionBrowse event using ControlEvent\_SpawnDialog.](http://source.winehq.org/git/wine.git?a=commitdiff;h=971ab9aa47476a56a1d6ee616fa332351c368f7b) |
| James Hawkins | 2006-10-03 | [msi: Store the selected item in the SelectionTree control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=908e27d6fcb8cb874912d610b6e5f9c311e721e8) |
| James Hawkins | 2006-10-03 | [msi: Publish the SelectionDescription and SelectionPath events when the selection ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=846fdd1550925803f1613fdad02f00bc1a4ddddd) |
| James Hawkins | 2006-10-03 | [msi: Select the first item in the SelectionTree control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7ee3a4efdf13b671dcf253fd4265d2d7f41944f1) |
| James Hawkins | 2006-10-03 | [msi: Subscribe the SelectionTree control to the SelectionPath event.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5ea2cd44c1766710bf6c944a1889e1e47c8bd15d) |
| James Hawkins | 2006-10-03 | [comctl32: Set the TVIF\_TEXT mask when notifying the parent window of a selection ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=3d2b37cc8391f9f02f6405649f33492adf1242b0) |
| James Hawkins | 2006-10-03 | [msi: Provide a specific dialog to ControlEvent\_SubscribeToEvent, as package-&gt;dialog ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=2a8c38ff74f0ba488934cdb0fd30fce3139ab43e) |
| James Hawkins | 2006-10-03 | [msi: Add missing '\n' to TRACE output.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1bfc50eb74f7a434039db54e78737d74062053f7) |
| James Hawkins | 2006-10-03 | [msi: Empty the window text if no text is provided.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0fe1b3671624ceb077598eac8f7deaa24469a671) |
| James Hawkins | 2006-10-03 | [msi: Don't ERR if a dialog doesn't provide control conditions, as they are not required.](http://source.winehq.org/git/wine.git?a=commitdiff;h=038d31ca93f0fee8af13b5863d3da07536de0945) |
| Benjamin Arai | 2006-09-29 | [resutils: Implements stub dll for resutils.dll.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3ac07aa0164a9e2923998789d77f6e7f20501d35) |
| James Hawkins | 2006-09-28 | [msi: A feature state of INSTALLSTATE\_ABSENT translates into a component state of ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=d83aa64c57072fad6960076ce3aab830e2cfe639) |
| James Hawkins | 2006-09-28 | [msi: Follow state resolution rules when a feature parent saves a component.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cabc7ee1ae327e4e29c3f9910498d83f48e56af7) |
| James Hawkins | 2006-09-28 | [msi: Implement MsiDatabaseImport.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6be7ba7546f9d38ca0d3b6006ff4895dad4d83fd) |
| James Hawkins | 2006-09-28 | [msi: Return to the parent dialog when the argument to the EndDialog event is Return.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3d812659e87c472a81a152f2ddfe27bd18801deb) |
| Benjamin Arai | 2006-09-27 | [clusapi: Implement stub dll for clusapi.](http://source.winehq.org/git/wine.git?a=commitdiff;h=493bc6b875d8c0c41e9a22da2c420216d4490c73) |
| James Hawkins | 2006-09-26 | [msi: Store the full path to the database file in the MSIDATABASE structure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=da14a4a25e686c5395164fb82c60d7b9590e7d50) |
| James Hawkins | 2006-09-26 | [msi: If the feature linked to a component has a state of INSTALLSTATE\_UNKNOWN, the ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=bbd4d1e3ef314098f1e7777629cb0bc7c347c330) |
| James Hawkins | 2006-09-26 | [msi: Only specifically resolve the TARGETDIR directory once.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ad609f15180b73f75f08d7e61223f70294befb71) |
| James Hawkins | 2006-09-26 | [msi: Add tests for setting the target path of TARGETDIR (based on a patch by Andrey ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=3ee3fc35ef9d2a3173b01b3bd925dc55a21bd7f3) |
| James Hawkins | 2006-09-22 | [setupapi: Fix a typo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5dadca4dbca70cd98db68f1fb2d5fa0c8348a636) |
| James Hawkins | 2006-09-21 | [msi: Load the component states in CostFinalize instead of CostInitialize.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d893cb7d1e1f52bf5e156f347e6300ccc449d7f9) |
| James Hawkins | 2006-09-21 | [msi: Initialize all features' action states to INSTALLSTATE\_UNKNOWN.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ca5c11009da675aae6407bcf5c74f57baab4d128) |
| James Hawkins | 2006-09-21 | [msi: Only override a feature whose action state is INSTALLSTATE\_SOURCE.](http://source.winehq.org/git/wine.git?a=commitdiff;h=937b9b2bbc0c2a264f124ddb5bd5e921e9eded02) |
| James Hawkins | 2006-09-21 | [msi: Translate the INSTALLSTATE\_UNKNOWN index into the INSTALLSTATE\_ABSENT image ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=703d77dc58a032b08dc222de951474a7f28f8fac) |
| James Hawkins | 2006-09-21 | [msi: Fix the results of a few tests to match Windows.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6ac0f3ed29802487898623d256a6906786416556) |
| James Hawkins | 2006-09-21 | [msi: Disable child features of parent features that are unselected because of the ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=545d0e70cf200270956193f6606eb2a9cbb2933a) |
| Benjamin Arai | 2006-09-21 | [msi: Adds test to check &quot;JOIN&quot; operator with &quot;\*&quot; operator for the SELECT clause retur ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=4195697cc1405ecc9de4bb0d10790bbf4d37dd32) |
| James Hawkins | 2006-09-21 | [msi: Don't check a component's install state if a component ID is not provided.](http://source.winehq.org/git/wine.git?a=commitdiff;h=32f570222be9e96b0e1730a4686163413451af95) |
| James Hawkins | 2006-09-21 | [advpack: backup should be a const string.](http://source.winehq.org/git/wine.git?a=commitdiff;h=319cac4c1fd497ba68445201b95278417b5cfd22) |
| Benjamin Arai | 2006-09-20 | [msi: Adds test to check if &quot;AND&quot; operator returns the correct result for the &quot;WHERE&quot; ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=f84c1463c1325528f6c664f3b369de3861a03cc2) |
| Benjamin Arai | 2006-09-20 | [msi: Adds test to check if basic &quot;JOIN&quot; operator without &quot;WHERE&quot; clause returns the ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=a35ff56580329de3a1dc2aa47029568550c23ba6) |
| Benjamin Arai | 2006-09-20 | [oleaut32: Conformance test for function variant:VarImp.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8d921f1d3cc0dac880e78817745f8255b9123aa3) |
| Benjamin Arai | 2006-09-20 | [oleaut32: Implementation for function variant:VarImp.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4cb6c9184b24f9be421306f15f9d1a05515c90a3) |
| Dan Hipschman | 2006-09-20 | [msxml3: Fix IXMLDOMNamedNodeMap\_getNamedItem() conformance on error.](http://source.winehq.org/git/wine.git?a=commitdiff;h=47b6d3a1e3a19796eb8b5a4578eba48a7fb23401) |
| Benjamin Arai | 2006-09-19 | [msi: Updates tests for joins to include row and column ids in message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d4c6b06ed7d73c63d9e9de7e6dd878594c85eaa7) |
| Benjamin Arai | 2006-09-19 | [msi: Adds tests to check if joins return the correct number of rows.](http://source.winehq.org/git/wine.git?a=commitdiff;h=32d002c7ed166348f62e613cf9784dbfcfd78e02) |
| James Hawkins | 2006-09-16 | [msi: Add tests for components with multiple parent features.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a4c6ca2b6551f822733284041b6bf8768b69bab4) |
| James Hawkins | 2006-09-16 | [msi: Use ACTION\_UpdateComponentStates in the selection tree so we don't have to dupli ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=7a97b3ed84baf36d7a09f5932d64f4daa819a890) |
| James Hawkins | 2006-09-16 | [msi: INSTALLSTATE\_SOURCE also overrides a parent feature state change to INSTALLSTATE ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=6518f3d7f2515b52a9c0d2f8a757998b41bd2ead) |
| James Hawkins | 2006-09-15 | [msi: Add the total and free disk space to the VolumeCostList control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=32c0a764ee898349b1278eab196e17b59fe1c1aa) |
| Benjamin Arai | 2006-09-15 | [nddeapi: Implement stub dll for nddeapi.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0b4eafada9e1b484c19ea99e64aeb57fea405478) |
| James Hawkins | 2006-09-14 | [wintrust: Add a stub implementation of CryptCATEnumerateMember.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ab5494e83ecde54f37ec02cf9fd20219d12baab1) |
| James Hawkins | 2006-09-14 | [wintrust: Add a stub implementation of CryptCATOpen.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a89db155d8aa9e70216ee8baae921deca653a8a0) |
| James Hawkins | 2006-09-14 | [wintrust: Move the Crypt\* functions to crypt.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8082477d6c0cdc3a413ad97515679cbb8aa53ad4) |
| James Hawkins | 2006-09-14 | [wintrust: Add a stub implementation of CryptCATClose.](http://source.winehq.org/git/wine.git?a=commitdiff;h=15b7934f3da0ccb2afc0976248a504fad2ca36d2) |
| James Hawkins | 2006-09-14 | [setupapi: Add stubs for SetupOpenLog, SetupCloseLog, and SetupLogError.](http://source.winehq.org/git/wine.git?a=commitdiff;h=15b46847b0bc4d9bcc2b03d9377ce7342f4da536) |
| Dan Hipschman | 2006-09-13 | [widl: Remove unused parameter in create\_msft\_typeinfo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bd7e690c1fbdf68cc8220e1a91b706ad946bc9cc) |
| Dan Hipschman | 2006-09-13 | [widl: Add -u and -U options to man page.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a472c83f9174e82ecd91dc37728afeba5a661fd5) |
| Dan Hipschman | 2006-09-13 | [widl: Replace a #if by if for better compiler checking.](http://source.winehq.org/git/wine.git?a=commitdiff;h=954c592a6c076626e2789415f86612404d30f8a1) |
| James Hawkins | 2006-09-13 | [setupapi: Implement pSetupGetField, with tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7588b669d8331ff64fc3b75cebe40ef518cd0de1) |
| Dan Hipschman | 2006-09-13 | [widl: Remove unused parameter in write\_ip\_tfs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6e7389ada8a7942031399a8763efa82eeb2ddfad) |
| Dan Hipschman | 2006-09-13 | [widl: Fix warning about unused structure field in lexer.](http://source.winehq.org/git/wine.git?a=commitdiff;h=53a28192865d212021ff4f3a573dd78f80584be0) |
| Dan Hipschman | 2006-09-13 | [widl: Remove unused parameter in ctl2\_encode\_name.](http://source.winehq.org/git/wine.git?a=commitdiff;h=48006f60a7462d889264a1c4839de015ee481cc1) |
| Dan Hipschman | 2006-09-13 | [widl: Don't compare result of read() to unsigned type.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3ad3f8de42658db331110bf14baa5b81be6c809a) |
| James Hawkins | 2006-09-12 | [msi: Add more join tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bfc1b5c15f35237e4234fca29f98079d59c4d69c) |
| Dan Hipschman | 2006-09-12 | [oleaut32: Replace a loop with a simple computation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b6e6d4b5115ff46c76ad390bb518bc50df09c7cb) |
| James Hawkins | 2006-09-12 | [msi: Show the available drives in the VolumeCostList control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=75ee2262cc3f49e7718cb114ae159bf3eaf6d167) |
| Dan Hipschman | 2006-09-12 | [widl: Replace a loop with a simple computation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6f4b83bce07100bdef792238260c66a1fa6bd589) |
| Benjamin Arai | 2006-09-11 | [oleaut32: Fixes for function variant:VarIdiv.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ed6499918058bc274357cd9b24081f14d84f8eee) |
| Benjamin Arai | 2006-09-11 | [oleaut32: Fixes for function variant:VarDiv.](http://source.winehq.org/git/wine.git?a=commitdiff;h=aaca30cf039c227ef03268e10abdea3afbe239f8) |
| Benjamin Arai | 2006-09-11 | [oleaut32: Conformance test for function variant:VarDiv.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a4ec2721a48508d672f2d7ca3c1b2d4d44836f4e) |
| Benjamin Arai | 2006-09-11 | [oleaut32: Conformance test for function variant:VarIdiv.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7e1f392a273b5a580c90cd599d5581db554f4a18) |
| James Hawkins | 2006-09-11 | [msi: Don't try to register a class if a COM server file is not provided.](http://source.winehq.org/git/wine.git?a=commitdiff;h=61db539cec1e44927b1c8ea8bf2d8c948800bd80) |
| Benjamin Arai | 2006-09-08 | [oleaut32: Fixes for function variant:VarPow.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fbf9cba6833701ddcd201138dec1ad0d6c1ee756) |
| Benjamin Arai | 2006-09-08 | [oleaut32: Conformance test for function variant:VarPow.](http://source.winehq.org/git/wine.git?a=commitdiff;h=aee8a62136f51b1784f271cb0aaecfc9fa806f6f) |
| James Hawkins | 2006-09-08 | [msi: Allow non-key columns to be used with the join query.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a302f03c6533abec30e6664e6e152d167000b773) |
| Benjamin Arai | 2006-09-08 | [oleaut32: Conformance test for function variant:VarAnd.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9e3e591bf24d4adcf3ce9aefb68eaad9c29f0009) |
| Benjamin Arai | 2006-09-08 | [oleaut32: Fixes for function variant:VarAnd.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3abb454c707ad6cb91dc23cb59e5ca5a5871bac2) |
| James Hawkins | 2006-09-07 | [msi: Add tests for MSI SQL join queries.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d8c13370b31d067c9edab7770cae31ee036652fa) |
| Dan Hipschman | 2006-09-07 | [widl: Add more complete pointer handling to write\_typeformatstring\_var.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6ff8ae327f783252407192c5ac431ec13f8e0db8) |
| James Hawkins | 2006-09-06 | [msi: Use the TargetPath of a file if the file doesn't exist in MsiFormatRecord.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ff6fe41df74a244282e8d38369d4d8da37141dba) |
| James Hawkins | 2006-09-06 | [msi: Add many more MsiFormatRecord tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f6463dfacdad2a1f6d0f12660c1b0a712a5176ed) |
| James Hawkins | 2006-09-06 | [msvcmaker: Remove a reference to libs/unicode in msvcmaker.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bedcdee7147d448af47193cca1ec65d20576f3c2) |
| James Hawkins | 2006-09-06 | [msi: Fix creation of the default format in MsiFormatRecord.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a248cc8f6284754c4b1abbe35ba42465437eb0b0) |
| James Hawkins | 2006-09-06 | [msi: Fix two MsiFormatRecord tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=16769b26b2bbd7adbca85eb93fe9b2c4dcd944f3) |
| James Hawkins | 2006-09-05 | [msi: Add more tests for MsiFormatRecord.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ad2ec01739dd8eaa565591a4b6888f3b4259002d) |
| James Hawkins | 2006-09-04 | [msi: Add the ability to change directories in the DirectoryList control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4969ccf3af4a72d93ae13043f50f0123d37ab989) |
| Dan Kegel | 2006-09-04 | [programs/wcmd: Rename to programs/cmd.](http://source.winehq.org/git/wine.git?a=commitdiff;h=39857443e4159d5c9e04fb93e158603b374f1a44) |
| James Hawkins | 2006-09-04 | [msi: Store the CustomActionData for deferred custom actions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0405e9d2d438878ab52bf6c0c52f522410163f0b) |
| Dan Hipschman | 2006-09-01 | [widl: Sanity check string and pointer attrs.  Don't assign string as type.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a407da47751912ff7ea4adad2e915c6357d0eb1a) |
| James Hawkins | 2006-09-01 | [msi: Load and display the VolumeCostList control's column headers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8f691adf7e4ac27d8ea0f45ca19b9b695244ffc7) |
| Dan Hipschman | 2006-09-01 | [widl: Handle more pointer types in get\_struct\_type.](http://source.winehq.org/git/wine.git?a=commitdiff;h=180ede5bfee6502a1950405d4cc17fe4941cf57c) |
| James Hawkins | 2006-09-01 | [msi: Add initial implementation of the DirectoryList control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=01432d71652857bbd0fc506b20718941e96613d2) |
| James Hawkins | 2006-08-31 | [msi: Verify the path in the PathEdit control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ad559ca86d8a48e8aebeed326d360edf5306d05f) |
| James Hawkins | 2006-08-31 | [msi: Search for the browse dialog controls by type instead of name.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9c3e640c100b90a928de7d9f45ab176dd88c7631) |
| James Hawkins | 2006-08-31 | [msi: Add more tests for the \_Streams table.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7e86590518504b8c9046db5b080150f5f85eefb0) |
| James Hawkins | 2006-08-31 | [msi: Provide the control to the dialog\_update function for the case](http://source.winehq.org/git/wine.git?a=commitdiff;h=4e3f6eda0e3af2a226e50044dca7baf9f97e479f) |
| James Hawkins | 2006-08-31 | [msi: Store and use the center point of the dialog window in between dialogs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1cfdc5185a86934b634674e7ff4654b4367aedca) |
| James Hawkins | 2006-08-30 | [crypt32: Simplify CRYPT\_AsnDecodeNameValueInternal, getting rid of a warning.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a9670e371e8d582147980a743c0073e95e5ac8ea) |
| Dan Hipschman | 2006-08-30 | [widl: Remove checks for typedefs that always fail.](http://source.winehq.org/git/wine.git?a=commitdiff;h=88820263c6ed440a0dcadefb6b1dd2316c20404a) |
| James Hawkins | 2006-08-30 | [crypt32: Simplify CRYPT\_AsnDecodeUnicodeNameValueInternal, getting rid of a warning.](http://source.winehq.org/git/wine.git?a=commitdiff;h=382d06794b40391b0cf7961dec89260735897dde) |
| James Hawkins | 2006-08-29 | [advpack: Get the proper working directory in install\_init.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f5acc51f2c495e32305a72de30fea82fd6f19379) |
| Dan Hipschman | 2006-08-29 | [widl: Use type\_t for typedefs, not var\_t.  Simplify representation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c117a20cdb5ffbe04fd334bd7139fdb9dd60978a) |
| Dan Hipschman | 2006-08-29 | [widl: Factor the entry\_t structure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=aadc90b2668ea641d4ed7dfba2b9f24f125f73b1) |
| James Hawkins | 2006-08-29 | [advpack: Add the regsvr action to the SetupInstallFromInfSection call.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a39913fa1199ff2bf1c2c7602ce688eea2295483) |
| Dan Hipschman | 2006-08-29 | [widl: Add an is\_ptr function.](http://source.winehq.org/git/wine.git?a=commitdiff;h=929a75989594cbc5e47772b36d89def30a5546e7) |
| Dan Hipschman | 2006-08-29 | [widl: Print pointers more aesthetically in generated header.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7e79e9d4fff058d95e45ed16fe514b20b54c4884) |
| James Hawkins | 2006-08-29 | [msi: Highlight the text in the PathEdit control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7df642117c2e23949a329ba6d070f7078427c0fe) |
| James Hawkins | 2006-08-29 | [msi: Update the DirectoryCombo control in response to the DirectoryListUp event.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6320d0adef3003d3bc941856c29c6bbb41f09df8) |
| Dan Hipschman | 2006-08-29 | [widl: Generate names for tagless structs, unions and enums.](http://source.winehq.org/git/wine.git?a=commitdiff;h=59cfad37aab59d307383f828d1ca79275efad453) |
| James Hawkins | 2006-08-29 | [msi: Update the PathEdit control in response to the DirectoryListUp event.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2dbaccbe606f7a1ddec13717ccb93f28457d9355) |
| James Hawkins | 2006-08-29 | [msi: Use the respective update functions when creating the Browse dialog control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2a09d4f6c722e400a0fc7473d8c7ff1c792e3b07) |
| James Hawkins | 2006-08-29 | [msi: Use msi\_dialog\_dup\_property where appropriate.](http://source.winehq.org/git/wine.git?a=commitdiff;h=20d98e81eda835a91524f2585f3253a806b968a5) |
| Dan Hipschman | 2006-08-29 | [widl: Generate an error for &quot;int f(void a)&quot;.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1687a5d1db2c0bcd3f7155c6195d500b7959010b) |
| Dan Hipschman | 2006-08-29 | [widl: Add the rest of the pointer types to write\_type.](http://source.winehq.org/git/wine.git?a=commitdiff;h=04a15af5dc9e0f68b1ee0cad2dbf8b9d642b35e0) |
| Dan Kegel | 2006-08-28 | [msi/tests: Add test to verify we can create 4000 msi handles.](http://source.winehq.org/git/wine.git?a=commitdiff;h=98ec9399c4ac33b84b6ff88338722e83f379d427) |
| Dan Kegel | 2006-08-28 | [msi: Callers of alloc\_msihandle should handle failure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=337e1e202f636404933cbb721366306f0d59b788) |
| Dan Kegel | 2006-08-28 | [msi: Remove limit on number of handles.](http://source.winehq.org/git/wine.git?a=commitdiff;h=29f0803c0239fe2495ffddd96471cd03475dc0db) |
| James Hawkins | 2006-08-25 | [msi: Add initial implementation of the DirectoryCombo control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a97962eef442016f4e2f550bdaede236a47c9925) |
| James Hawkins | 2006-08-25 | [msi: Add initial implementation of the DirectoryListUp event.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a1b16d2d96c7d7e29bf9fd7dfccd45436242ea5e) |
| Dan Hipschman | 2006-08-25 | [widl: Remove usage of type\_t ref field for base types; simplify code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=94755218aca1e1597f2b1a5562e1b71cfad13259) |
| James Hawkins | 2006-08-25 | [msi: Add a stub implementation of the VolumeCostList control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=80225d53b945caa68b58f4f67cd9c512ebacbcc7) |
| James Hawkins | 2006-08-24 | [msi: Inform the user with an error message when the MSI file path is invalid.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fb7646beaa1a76f40ed0e05ab0dd7c36034439b7) |
| James Hawkins | 2006-08-24 | [msi: Add a stub implementation of the DirectoryCombo dialog control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c9674e690c053c4be05e4b651909e7702d18f442) |
| Benjamin Arai | 2006-08-24 | [oleaut32: Updated conformance test return string for VT\_RESERVED.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6aaf2af5c0b95d7599bfc02425f0961b96504dcf) |
| James Hawkins | 2006-08-24 | [msi: Add a stub implementation of the DirectoryList dialog control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=25062556a8f06c5064904a0096ddddda2bdd0957) |
| James Hawkins | 2006-08-24 | [msi: Add an initial implementation of the PathEdit control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=11b7097df8b12b4a4b7bd6485365089d502f9cec) |
| James Hawkins | 2006-08-24 | [msi: Fix the height of the line control window.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0de9cf4d002964eef7b2c4fa51c6e7e478286e09) |
| James Hawkins | 2006-08-23 | [msiexec: Add handling for msiexec's regserver option.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a6b8ff9ddbf4ee03e570d9e3b7ec925b34cc0361) |
| Benjamin Arai | 2006-08-22 | [oleaut32: Add support for handling TKIND\_COCLASS in userdefined\_to\_variantvt.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d1282dce887f2c17d99a633a59fda81bb17d78f5) |
| James Hawkins | 2006-08-22 | [msi: Add tests for the AppSearch action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=80740e72e7410a7560644fa83b8af3c20802441d) |
| James Hawkins | 2006-08-21 | [msi: Add tests for MsiEvaluateCondition's substring operators.](http://source.winehq.org/git/wine.git?a=commitdiff;h=762a13eb348010b140f3c779e0a0147dd87fd979) |
| James Hawkins | 2006-08-21 | [msi: Add handling for MsiEvaluateCondition's substring operators.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6a520c0b6d6eb92c92f8172e58f41e01d7c59032) |
| Dan Kegel | 2006-08-20 | [mpr: Fix bug in ProviderOrder comma processing in wnetInit().](http://source.winehq.org/git/wine.git?a=commitdiff;h=50ed26c358e74a0380c9514792e0de6fb844ce27) |
| Dan Hipschman | 2006-08-18 | [widl: Allow format-string functions to work with objects.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9b16916ed13e0b26ab3f375f2deb5cb146fda1b3) |
| Dan Hipschman | 2006-08-18 | [widl: Output format-strings for interface pointers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3870bf0d9e69924ac98633f5a0b541f77ec8f144) |
| Dan Hipschman | 2006-08-17 | [widl: Use typegen.c format-string functions in proxy.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ed10b24e14cd13d68fa380683f805a617d67dabc) |
| Dan Hipschman | 2006-08-17 | [widl: Move format-string declaration output to typegen.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b7e7243a1e5a4eb17c868246d075751fb1c1ac45) |
| Dan Hipschman | 2006-08-16 | [widl: Fix NdrComplexStructUnmarshall calls in generated code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e77a079b279ba168ab9d2d66390d2f2247edfafd) |
| Dan Hipschman | 2006-08-16 | [widl: Fix out-only temporary variable generation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c526c980d7ac68e0918c278bfccc50e118fe3ea9) |
| Dan Hipschman | 2006-08-16 | [widl: Fix NdrConformantArrayUnmarshall calls in generated code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b17d1c14d955fcce557010e5ee1cf777db919d32) |
| Dan Hipschman | 2006-08-16 | [widl: Generate proxy code for user marshalled types.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a5ff173cc3dccbe63185420158fcc8a620a6cc1d) |
| James Hawkins | 2006-08-15 | [msi: Use the bare minimum number of parameters for LookupAccountName.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d4a27358a57ff2f398c63de6c2dc688ed8f06d7b) |
| James Hawkins | 2006-08-15 | [msi: Add a stub for MsiGetFeatureCost.](http://source.winehq.org/git/wine.git?a=commitdiff;h=485484deace78519bf7309030400fab0f4d3d2ca) |
| Dan Hipschman | 2006-08-15 | [widl: Calculate method indices in parser instead of during header generation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=16d4e712301e4e10159807ec261b321b4a2665d5) |
| Benjamin Arai | 2006-08-14 | [oleaut32: Conformance test for olefont:ReleaseHfont.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c4ba8a8c87b3fab44422546f70f1bf0dfc433fa4) |
| Benjamin Arai | 2006-08-14 | [oleaut32: Conformance test for olefont:AddRefHfont.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bf6867024cb5ecd01429ba38ce79c1d4fda48354) |
| James Hawkins | 2006-08-14 | [msi: Non-compressed files may come before the list of compressed files in the file ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=75cc5f1e5e174d8a926b90a5eb004d5f6729e504) |
| Dan Hipschman | 2006-08-14 | [widl: Pass the right size to MIDL\_memset in generated proxy code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=47519f08a706b81db78391768a6027eb6d116076) |
| Dan Hipschman | 2006-08-12 | [widl: Improve pointer null checking logic.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9e49a8d2f2465030b1502031a8201354fa04f11d) |
| Benjamin Arai | 2006-08-12 | [oleaut32: Added test to check if olefont:IFont\_QueryInterface increments ref counter.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0b44e9a64192c2244614dbb3dd42284f95c62dd0) |
| Dan Hipschman | 2006-08-12 | [widl: Use ref\_type to simplify some code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=06497dd44c2d9cacbfabe3384d2e7433675dc0e8) |
| Benjamin Arai | 2006-08-11 | [oleaut32: Removes stub message from olefont:OLEFontImpl\_FindConnectionPoint.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3dade1e7def970bffd0aeac5d34b831e1ea37ed1) |
| James Hawkins | 2006-08-11 | [msi: If a component's state is not local, source, or default, default to the local ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=3cb82ab8d29561637fe46a532ebca0d300cbfce2) |
| Dan Hipschman | 2006-08-11 | [widl: Don't generate indentation spaces on empty lines.](http://source.winehq.org/git/wine.git?a=commitdiff;h=05001b1ca8bce4dce7c958e4732779706372cb62) |
| Dan Hipschman | 2006-08-10 | [widl: Fix incorrect version number in generated code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a20f7f46dcc032478e966c2301d05002440b8423) |
| James Hawkins | 2006-08-10 | [msi: Only remove a file if the version to be installed is strictly newer than the ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=5d37be9e56e9b875142a93a7af0671f2d9bc2947) |
| Dan Hipschman | 2006-08-09 | [widl: Add ref\_type (dereference typedefs) and use it.](http://source.winehq.org/git/wine.git?a=commitdiff;h=216171fe523c053d4aa28f3e242f029d7632849d) |
| James Hawkins | 2006-08-09 | [msi: Download install cabinet files if the msi package is remote.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1ff96c63a82d8192454d3513a4e0110c1bc02026) |
| James Hawkins | 2006-08-08 | [msi: Add tests for the RemoveFiles action.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bf4e00fd9bb0188df43d09720cf6ca4c5efb184a) |
| James Hawkins | 2006-08-07 | [msi: Fix the compressed files logic.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f84fa0ce6354827d6b2396ca3119c9a8bb7efcfb) |
| James Hawkins | 2006-08-07 | [wintrust: Always return ERROR\_SUCCESS in WinVerifyTrust.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f5e0195be642117e0380db1bbdf8d1a55cb4e383) |
| James Hawkins | 2006-08-07 | [msi: Add tests for MsiGetProperty.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4fade6d3a85df6872d676d33fcee1a0666f8e73c) |
| Dan Hipschman | 2006-08-04 | [widl: Generate GUID (infile\_i.c) files.](http://source.winehq.org/git/wine.git?a=commitdiff;h=df91150e10c093933bd4fd685a68885f38067b8e) |
| Dan Hipschman | 2006-08-04 | [user: Call SetLastError in CreateWindowEx when WS\_CHILD is set with no parent.](http://source.winehq.org/git/wine.git?a=commitdiff;h=74ece17c6bd141c5a13b3aec7522303fb50bc472) |
| Dan Hipschman | 2006-08-04 | [user: Add a test for CreateWindowEx.](http://source.winehq.org/git/wine.git?a=commitdiff;h=50486859706d01f5d639d8029a5cba71bdd9ccae) |
| Dan Hipschman | 2006-08-04 | [widl: Replace strdup, malloc and realloc with xstrdup, xmalloc and xrealloc.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4961379d7408cc6f080106b0c01e85eb014da17d) |
| James Hawkins | 2006-08-04 | [msi: Use the initial dialog position values in the database when creating the dialog ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=23027f54356286907f5fec525059222a243284fd) |
| Benjamin Arai | 2006-08-04 | [oleaut32: Removes extra string allocation for varformat:VarMonthName.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0227b8cba228b17159a6ca392b801eda38815dca) |
| Dan Hipschman | 2006-08-03 | [widl: Write forward declarations for coclass definitions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=99056d7e2ac56e11a4f6c101463c705abb611bf1) |
| Thomas Kho | 2006-08-03 | [server: Remove unused thread\_apc member.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3538c0cdce81e1ee0861b0651da734aef14f0cfa) |
| Benjamin Arai | 2006-08-02 | [oleaut32: Implement function olefont:OLEFontImpl\_IsEqual.](http://source.winehq.org/git/wine.git?a=commitdiff;h=be37e9510568c5e6afd2ffd7de3a70a42aed5d13) |
| James Hawkins | 2006-08-02 | [msi: Add tests for SQL query markers.](http://source.winehq.org/git/wine.git?a=commitdiff;h=91ec65d7f150a7951d4b17119447bfb9167bcaa2) |
| Benjamin Arai | 2006-08-02 | [oleaut32: Conformance test for olefont:OLEFontImpl\_IsEqual.](http://source.winehq.org/git/wine.git?a=commitdiff;h=41641554f4c4563a0c794375bc7ce60d13201c88) |
| James Hawkins | 2006-08-01 | [msi: Don't crash if an empty record is given to MsiProcessMessage.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f10365bb5dd9a0994368dfd82834691db5250598) |
| Thomas Kho | 2006-08-01 | [msi: Wake dialog on messages from external threads.](http://source.winehq.org/git/wine.git?a=commitdiff;h=88cc410fd62f51c52e052c1ca50a1380686ed513) |
| James Hawkins | 2006-08-01 | [msi: Set the install state to INSTALLSTATE\_LOCAL for features with compressed files.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7edea0cc6868505252c65cbf0846b2f577660e51) |
| James Hawkins | 2006-08-01 | [msi: A file that does not have the msidbFileAttributesCompressed bit set should be ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=1dd97aa15428c0fc97a4f909f28f252f4d85723d) |
| Dan Hipschman | 2006-08-01 | [oleview: Initialize TVITEM.lParam to NULL in EnumFuncs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=10d552b22ef60a755584cf9e980c52beb8e50731) |
| James Hawkins | 2006-07-31 | [setupapi: Add a stub implementation of SetupGetSourceInfo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b74f4d92d74953eabb594a17c91fb6a6aff60ee7) |
| James Hawkins | 2006-07-31 | [msi: Set the install state to INSTALLSTATE\_LOCAL for components with compressed files.](http://source.winehq.org/git/wine.git?a=commitdiff;h=98d148641046bba33845b11178b76be121ae2b0f) |
| Benjamin Arai | 2006-07-31 | [oleaut32: Move varformat conformance tests to new file varformat.c](http://source.winehq.org/git/wine.git?a=commitdiff;h=63c26dac23323d94599efe70caf86cf3ba61b7c2) |
| James Hawkins | 2006-07-31 | [msi: Fix the add\_feature\_entry helper function.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6330f14da9d3a7519cb59e14a37f128d77f6dee4) |
| Thomas Kho | 2006-07-31 | [riched20: Implement EM\_GETLINE.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3f19ffe809aa68a2936ae6a3b0df677932fd0ef7) |
| Dan Hipschman | 2006-07-31 | [widl: Set type\_t kind field correctly for all types.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3e1ace5aa32c2995cedb0f75e3635a4ef57da0ed) |
| James Hawkins | 2006-07-31 | [msi: Fix a couple install state test cases.](http://source.winehq.org/git/wine.git?a=commitdiff;h=38f2ba23f1a9f877f220e9776ad19f9d99492bd2) |
| Dan Hipschman | 2006-07-31 | [widl: Set defined flag for coclasses.](http://source.winehq.org/git/wine.git?a=commitdiff;h=23707beb461c7c44a17088de4c78d4f654ca2091) |
| Dan Hipschman | 2006-07-29 | [widl: Fix &quot;static declaration follows non-static declaration&quot; in generated code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cf4c08dcbc34ee1a9cbc68bcbf9b30da5eb09e69) |
| Benjamin Arai | 2006-07-28 | [oleaut32: VarSub: Conformance test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f10ed1f16eaac58e04bed943f608833269840f54) |
| Dan Hipschman | 2006-07-28 | [widl: Fold class\_t into type\_t.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c67b19b4f4bd463eedfbd4de77b846f9efb8a040) |
| Dan Hipschman | 2006-07-28 | [widl: Check if a typeinfo is already in a typelib before adding it.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c650cceae32849ea974328a94753cd2cef94a9c1) |
| Benjamin Arai | 2006-07-28 | [oleaut32: VarSub: Fixes several data types and corrects error codes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9634ffa7dca3f42a7aeae9a9bb62c2bddf84e289) |
| Dan Hipschman | 2006-07-28 | [widl: Register types for coclasses.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9265d775849b0181fb3cd7efe244082128ca82a7) |
| Dan Hipschman | 2006-07-28 | [widl: Set typelib\_idx for coclasses when they're added to a typelib.](http://source.winehq.org/git/wine.git?a=commitdiff;h=90cdff9b3fbe0380cf38effb714376b26041359f) |
| James Hawkins | 2006-07-28 | [wininet: Only copy the relative filename into the UrlEntry structure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8c6040fccc2d8c8c9b3481f6ac0575e69ed3fbcd) |
| Dan Hipschman | 2006-07-28 | [widl: Encode coclass types in typelibs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=678ce9875f8e13c559caf457bccab6811a1cf082) |
| Thomas Kho | 2006-07-28 | [Maketest.rules.in: Fix comment.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1afed1f8d8aaa46ec74e8f5cfa0b3c281ab92687) |
| Benjamin Arai | 2006-07-28 | [oleaut32: VarMonthName - Update error codes and helper functions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0eed4603c506b1c0495b592489c5a4e6282ad0e1) |
| James Hawkins | 2006-07-28 | [msi: Add tests for MsiDatabaseImport.](http://source.winehq.org/git/wine.git?a=commitdiff;h=05bd17b8b7e27b555c4c6c21158da659aef08ca9) |
| James Hawkins | 2006-07-26 | [msi: Download the MSI package if it is a remote URL.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d1617bea17b8614303ef5b19851e18f25b66a250) |
| James Hawkins | 2006-07-26 | [msi: Test the column types of MSI packages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=75c866ed58c5fcab66dc826249bb6f096bcb8608) |
| James Hawkins | 2006-07-26 | [msi: Test the states of a component with a compressed file.](http://source.winehq.org/git/wine.git?a=commitdiff;h=59a706bc2b60dcd74d528405194228d41383ed59) |
| James Hawkins | 2006-07-26 | [msi: Fix a typo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5842af1b951d5deb552130ea27da95e8f816a44e) |
| Thomas Kho | 2006-07-25 | [wcmd: Correct handling of quotes and /s flag when a command argument is present.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bff25ffe7991bde75904d34ca733f2178b088316) |
| James Hawkins | 2006-07-25 | [msi: Add tests for the WHERE SQL clause.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8144e171697bc3543c4c0b2ddd743ca3827db669) |
| Dan Hipschman | 2006-07-25 | [widl: Allow trailing commas in attribute lists.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3b3632a1cd0e8c4633f00ac97325e583ebadaf60) |
| Dan Hipschman | 2006-07-24 | [widl: Fix redefinition of types in output.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f3d01fb07b38858c28156eb1ec1799765f65fd20) |
| Dan Kegel | 2006-07-24 | [winedos: Limit reported disk space to 1GB.](http://source.winehq.org/git/wine.git?a=commitdiff;h=91f9746d2f8f564a508351490205b7c7a64b718e) |
| Dan Hipschman | 2006-07-24 | [widl: Support SAFEARRAY(type) syntax.](http://source.winehq.org/git/wine.git?a=commitdiff;h=12a9dfd62fcfb0be520b0bba2954b780dc994329) |
| James Hawkins | 2006-07-21 | [msi: Expand features with odd Display values.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e295bd97431fefdeac74f4c5c340c266bae1dd75) |
| James Hawkins | 2006-07-21 | [msi: Add tests for component and feature states.](http://source.winehq.org/git/wine.git?a=commitdiff;h=dc0aad523ba7fa6fcb511ed9f080d3807b5b4cc8) |
| James Hawkins | 2006-07-21 | [msi: Don't display a feature if its Display value is zero.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cf9886e6e0a4c6a862d88d26b8eaf7b6f9b8c6a5) |
| James Hawkins | 2006-07-21 | [msi: Set the component's initial state based on its attributes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cae3215a6fd78446fd356cb8720dd70adc734d69) |
| Benjamin Arai | 2006-07-21 | [oleaut32: Fix missing tests and heap errors for VarCat conformance.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b636e4dbf43c9054fb3ce66e674d1fdc8dd6be5b) |
| Dan Hipschman | 2006-07-21 | [widl: Allow write\_type to output full pointer types.](http://source.winehq.org/git/wine.git?a=commitdiff;h=82c11ce0025e386308623671f126646d0724051a) |
| Thomas Kho | 2006-07-21 | [server: Add new threads to end of thread\_list.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4ff4ba394ed56b2ea94553f90ed7935e85669914) |
| Benjamin Arai | 2006-07-21 | [oleaut32: Fix temp variant initialization issues in VarCat.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4026a4c0a8d47f558ce1d303a9d8b92270e16474) |
| Benjamin Arai | 2006-07-20 | [oleaut32: Implements OLEFontImpl\_GetIDsOfNames.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f75b9f190f368956949277983a09757d3e5b1a67) |
| Benjamin Arai | 2006-07-20 | [oleaut32: OLEFontImpl\_GetIDsOfNames conformance test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=31e3ad7150f5e308e5ead6f49fa0e87f7d2bafc4) |
| James Hawkins | 2006-07-19 | [msi: Implement the SetInstallLevel event.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ece0ae0a41b74f9ee37ad1dbe3835e82e997641c) |
| James Hawkins | 2006-07-19 | [msi: Forward MsiSetInstallLevel to an internal MSI\_SetInstallLevel that can be used ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=de73481c894ccea076fe53af5b743c77cfe7d1f5) |
| James Hawkins | 2006-07-19 | [msi: Rename SetFeatureStates to match the naming scheme of internal msi functions.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7c7f0bb2c18b23003bd7c63cb9e8b9ab90cf9cec) |
| James Hawkins | 2006-07-19 | [msi: Update feature states after changing install levels, as they may have changed.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7bcac31dcf4b37a0780efaf06540351e2c3543b3) |
| James Hawkins | 2006-07-18 | [msi: Add a stub implementation of MsiSourceListClearAll.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fc56e92657ddb67c6374e51ae23b90207d44049b) |
| Benjamin Arai | 2006-07-18 | [oleaut32: Update error codes for VarMod.](http://source.winehq.org/git/wine.git?a=commitdiff;h=911af4dce9c0b0d5984491baae7e515647519d2e) |
| James Hawkins | 2006-07-18 | [msi: Sort SelectionTree items by their Display value.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2396e2a59f822dd10975e82ed8224e1fe4b883c7) |
| Benjamin Arai | 2006-07-17 | [oleaut32: VarCmp - Corrected function description.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d42002b72c1218a8e46c3df2582ee05b4e8fe412) |
| Dan Hipschman | 2006-07-17 | [wpp: In recursive macro definitions, print the macro name instead of nothing.](http://source.winehq.org/git/wine.git?a=commitdiff;h=804993deeababf0c80af65e8a95ab2ec4e4bce0a) |
| James Hawkins | 2006-07-17 | [msi: Update the feature components' states when a feature is selected.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7745a831a13adc0c8f55911009c3b2b57b8fa754) |
| Dan Hipschman | 2006-07-14 | [widl: Fix unterminated comment in generated code.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d68ec1d325e17b45194af58e455a567a79f45462) |
| James Hawkins | 2006-07-14 | [wininet: Add more tests for InternetCrackurl.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a1544731dbaf30c473be2ae254f2f24e3138babf) |
| James Hawkins | 2006-07-14 | [msi: Add handling for the ListBox dialog control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6de2ca845983dd93c3e9cdda97e8f6019b5f1f2f) |
| Dan Hipschman | 2006-07-14 | [widl: Support coclass forward declarations.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2660b8f9c190890faf7f22054344e238f0b3edb5) |
| James Hawkins | 2006-07-13 | [shlwapi: Add tests for PathCommonPrefixA.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c70bf5aaab747ca8966536d64c0047f1959001d6) |
| James Hawkins | 2006-07-13 | [shlwapi: Add tests for PathBuildRootA.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a6f4ede2557d83c2f659b8f320e2b53658ac8448) |
| James Hawkins | 2006-07-13 | [msiexec: Also support options using a hyphen.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8c3fc3a889bd6c5e0dc965d0aec4dad9fc5937db) |
| James Hawkins | 2006-07-13 | [msi: Add handling for the GroupBox dialog control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1adcf0087af491d2f1413d87ae225b17101568fc) |
| Dan Hipschman | 2006-07-12 | [gdi32: Add conformance test for GetTextExtentExPointW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fe3c9428c3975259e50eb2d87f60307fda154144) |
| Dan Hipschman | 2006-07-12 | [gdi32: Implement GetTextExtentPoint in terms of GetTextExtentExPoint](http://source.winehq.org/git/wine.git?a=commitdiff;h=f9047238134e1dbfd7eaedf81a6ee94788a4681d) |
| Thomas Kho | 2006-07-12 | [notepad: Change file not saved alert title to match Windows' notepad.exe.](http://source.winehq.org/git/wine.git?a=commitdiff;h=724dd10ee80fe8b909c914dca07be13dacf251e0) |
| Thomas Kho | 2006-07-12 | [notepad: Change window title to be like Windows' notepad.exe.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3ec165fd990d1d62bfa5dacb30d2592285c4917f) |
| James Hawkins | 2006-07-12 | [msi: Update the files target paths as well, because a parent directory might have ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=094915ae2c12f1b3122462890bcda20b8cb70f7c) |
| James Hawkins | 2006-07-11 | [urlmon: Implement URLDownloadToCacheFileW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e2bf4ff16449d4c90d2a9fb662dc0f506d7bcbbc) |
| Benjamin Arai | 2006-07-10 | [oleaut32: Conformance test and patch for VarCat.](http://source.winehq.org/git/wine.git?a=commitdiff;h=700adac9aca86a0aab85952ac0d4472a2e4dd842) |
| James Hawkins | 2006-07-10 | [msi: AppSearchReg shouldn't create the key it's looking for if it doesn't exist.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3b506c640866025eb791e806d756330cdb2b01d0) |
| James Hawkins | 2006-07-10 | [msi: Test how SetTargetPath affects the target paths of install files.](http://source.winehq.org/git/wine.git?a=commitdiff;h=15ad5de13c7046d65a1e7c9b6153dfc8e6dd7c62) |
| James Hawkins | 2006-07-08 | [advpack: Add tests for different configurations of INF filenames and](http://source.winehq.org/git/wine.git?a=commitdiff;h=ac9e421999a98598ba05e72a397f776d0c7bf698) |
| Thomas Kho | 2006-07-08 | [winex11: Use correct multiplier for negative relative mouse movements.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4598c973b22bb7d7bd4436866d29e86ef3e0644d) |
| James Hawkins | 2006-07-06 | [advapi32: Add tests for LookupAccountSid.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ce58c3589ca98cfaeafb5f2b5e8902732483b315) |
| James Hawkins | 2006-07-06 | [advapi32: Get the token type in ImpersonateLoggedOnUser.](http://source.winehq.org/git/wine.git?a=commitdiff;h=409c6dc7b00a8ea6e1321d7f00b032bfe37711d7) |
| Thomas Kho | 2006-07-06 | [notepad: Change window classname from NPClass to Notepad.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0796fe256be7205ee336f2746c91daeb319938f3) |
| James Hawkins | 2006-07-03 | [wininet: Use a blank password if none is provided in FTP\_Connect.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8e96015ebb47c86625f70efac6b702122968636e) |
| James Hawkins | 2006-07-03 | [wininet: Error out if hInternet is a bad handle.](http://source.winehq.org/git/wine.git?a=commitdiff;h=545309c97fef6272b86563ca7bd7dbc856681038) |
| Thomas Kho | 2006-07-01 | [wcmd: Modify option parser to allow compound options.](http://source.winehq.org/git/wine.git?a=commitdiff;h=543716e1148bf67ca1e0130bf84cd77ff60ecd80) |
| James Hawkins | 2006-06-29 | [shlwapi: Add tests for PathCanonicalize.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b333f0c4d2babe40ab16a7a3f558266c94fd96b5) |
| James Hawkins | 2006-06-29 | [shlwapi: Add tests for PathFindExtensionA.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ad064915c957dd89e322bfe868c3b4c0d0c8e70a) |
| James Hawkins | 2006-06-27 | [msi: Read the font color from the database, and use it for the text control.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3c56550ea5141b48ec19a7a44b3e49f0bf7c6b2e) |
| James Hawkins | 2006-06-27 | [shlwapi: Add tests for PathAppendA.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3a1a607a008f4ad1b5f1c3a248199fb2a12e277b) |
| James Hawkins | 2006-06-26 | [shdocvw: Upgrade the version to 5.50.4134.599.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e391387c9acc68ea84b8966f635d46be5d7b0134) |
| James Hawkins | 2006-06-26 | [setupapi: Fix SetupCloseInfFile when a NULL handle is given, with tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bce44161f1f836fbe53a6c2be6ca16478810f0d5) |
| James Hawkins | 2006-06-26 | [msiexec: Use CommandLineToArgvW instead of process\_args to reduce code duplication.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7c35db000b26852fc2bf4a7a7e349953f60d183f) |
| James Hawkins | 2006-06-26 | [shlwapi: Add tests for PathCombineA.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7412bddd363b22186d14e13e373bbf64cc116751) |
| James Hawkins | 2006-06-26 | [shlwapi: Add tests for PathAddBackslash.](http://source.winehq.org/git/wine.git?a=commitdiff;h=251d76888d70133d3afa2cb8c43a45420175d8c2) |
| James Hawkins | 2006-06-23 | [shell32: Add missing multiply by sizeof(WCHAR)l](http://source.winehq.org/git/wine.git?a=commitdiff;h=f921fa544aeb018286d49e58343f1c61ab4924fe) |
| James Hawkins | 2006-06-22 | [msi: Add tests for components that aren't associated with a feature.](http://source.winehq.org/git/wine.git?a=commitdiff;h=566beb788b75c3c94aa7d9d6c8601b468a5116ef) |
| James Hawkins | 2006-06-21 | [atl: Add a stub implementation of AtlModuleLoadTypeLib.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b865c07db978fc846484d895654bb2fac1051004) |
| James Hawkins | 2006-06-21 | [mapi32: Add a stub implementation of MAPIOpenLocalFormContainer.](http://source.winehq.org/git/wine.git?a=commitdiff;h=092166696d05f0d1358a2153846d0377c7d98502) |
| James Hawkins | 2006-06-20 | [tools/wine.inf: Add d3d8.dll to the fake dlls list.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ce24c2a8a706cb016c2aaef7deb629e4ba7cca93) |
| James Hawkins | 2006-06-20 | [msi: Fix handling of the no-op identifier in the Directory table.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a1910e11bb4608469d2e70da7c00c651c0e12360) |
| James Hawkins | 2006-06-20 | [advpack: Implement DoInfInstall on top of the install framework.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1a0208ef612708c7dd8e570760758d7da2405f9c) |
| James Hawkins | 2006-06-15 | [msi: Add tests for MsiInstallProduct.](http://source.winehq.org/git/wine.git?a=commitdiff;h=36bf71c17405c5efe469ebe8227e1f25c0e816ee) |
| James Hawkins | 2006-06-05 | [oleaut32: Only BYREF DispCallFunc args whose input args are not BYREF should be changed.](http://source.winehq.org/git/wine.git?a=commitdiff;h=585763ffa91ba10291e2a2eff27b7dd8fd623611) |
| James Hawkins | 2006-06-05 | [oleaut32: Copy BYREF args directly if they have the same variant type.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0e5bd51d28eaa3a7d72c583f7cd822218ca4b351) |
| Thomas Kho | 2006-04-28 | [user: Extend menu conformance test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bde9ca2b63a5e2d04bcd6a1c94d7bf04f4922d02) |
| Thomas Kho | 2006-04-27 | [user: Fix behavior when selecting disabled menu items.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b8338605794c357eb7c1d319f3eec62a2efff3ea) |
| Thomas Kho | 2006-04-27 | [user: Allow menu WndProc to recognize VK\_[LR](http://source.winehq.org/git/wine.git?a=commitdiff;h=76104e1ccc2875dbb14331764913c07e75f3d0b7)MENU.] |
| Dan Kegel | 2006-04-22 | [msi: Fix missing case in MsiSourceListAddSourceEx.](http://source.winehq.org/git/wine.git?a=commitdiff;h=35f9a4797f52ae5e697c096015a9bafdd6a2c52e) |
| Thomas Kho | 2006-04-19 | [x11drv: Virtual key input scrubbing in X11DRV\_send\_keyboard\_input.](http://source.winehq.org/git/wine.git?a=commitdiff;h=75cd5e2101fb49ee9a7aca2f661d23604e7f619c) |
| Huw Davies | 2006-04-18 | [gdi32: Fix {Bit,Stretch}Blt fallbacks to StretchDIBits.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bf23ad0da7430afe69d2aff2a2b0549c05458db9) |
| Jacek Caban | 2006-04-14 | [shdocvw: Better window handling.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b81b614da824e54c80f7e32dcf2672519bbe20ce) |
| Jacek Caban | 2006-04-14 | [shell32: Don't crash in SHELL\_ExecuteW if psei-&gt;lpDirectory is NULL.](http://source.winehq.org/git/wine.git?a=commitdiff;h=150bd5442cf6037f2760e42592190e62ea055edb) |
| Mike McCormack | 2006-04-13 | [wtypes.idl: Add size attribute to a void pointer.](http://source.winehq.org/git/wine.git?a=commitdiff;h=54d3060a2db33e160c144dd0bbd787c859ddd73a) |
| Mike McCormack | 2006-04-13 | [widl: Add support for VT\_I8 and VT\_UI8 to msft typelibs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1d453ab55139fe1481eb78640966ecd7fa3d73b3) |
| Aric Stewart | 2006-04-13 | [comctl32: Listview notify fix.](http://source.winehq.org/git/wine.git?a=commitdiff;h=097aec39ca86fb84cda58c1db0b84c2c035b1ef4) |
| Jacek Caban | 2006-04-12 | [shdocvw: Use GetClientRect, not GetWindowRect in create\_doc\_view\_hwnd.](http://source.winehq.org/git/wine.git?a=commitdiff;h=51bd5408d4b411924123bde72bae95fa9b00fa55) |
| Jacek Caban | 2006-04-12 | [shell32: Allocate wszApplicationName on the heap as it may be longer than MAX\_PATH.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4b5125a79c4432b8d54f306418b175a51d6190ad) |
| Dmitry Timoshkov | 2006-04-12 | [avifil32: Avoid not necessary zeroing out of an allocated memory block.](http://source.winehq.org/git/wine.git?a=commitdiff;h=14aab5f3cb34cca8d24244622464eec39ae09a65) |
| Thomas Kho | 2006-04-12 | [x11drv: Properly handle VK\_LMENU input.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0e81484c45863b4005023f0159661f746a4a3d50) |
| Mike McCormack | 2006-04-11 | [shdocvw: Move the private class factory declaration into factory.c.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c1caf43d10918f7f422b7c5ef4ea5d3c323da8d6) |
| Mike McCormack | 2006-04-11 | [avifil32: Fix a regression caused by patch removing GlobalAllocs by using HEAP\_ZERO ...](http://source.winehq.org/git/wine.git?a=commitdiff;h=aebc88d54bdc6d4a835d8a023aa1862114ee4d4d) |
| Mike McCormack | 2006-04-11 | [shdocvw: Register iexplore.exe as a COM local server.](http://source.winehq.org/git/wine.git?a=commitdiff;h=42c7372b6b8c64b8f6e9ea378c283d0903988bfd) |
| Jacek Caban | 2006-04-10 | [docobj.idl: Fix some enums declarations.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fc01e11eac8264799a18ae432e7b0d3264820b35) |
| Jacek Caban | 2006-04-10 | [exdisp.idl: Added SHDocVw type library declaration.](http://source.winehq.org/git/wine.git?a=commitdiff;h=91d7bb5211da89d80658159baad060c86b0129c3) |
| Jacek Caban | 2006-04-10 | [exdisp.idl: Added missing declarations.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5e99bd94f1a7251d68367d880e4e292d9f1b2cea) |
| Jacek Caban | 2006-04-10 | [exdisp.idl: Added missing attributes and fix some arguments names.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5d5a380e9ef862b282df86140fe177451155c604) |
| Jacek Caban | 2006-04-10 | [exdisp.idl: Move declarations to better match to IE SDK.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5d3cef6dc9bffea5aedf70f618ee90070f6f7226) |
| Dan Kegel | 2006-04-09 | [x11drv: Fix two clipboard bugs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d5292cb3f43c882d46e8a83475b047edec0ea633) |
| Jacek Caban | 2006-04-08 | [mshtml: Fix ref counting.](http://source.winehq.org/git/wine.git?a=commitdiff;h=417c10476041079a20143314de5c49bdf2e4dafe) |
| Alexandre Julliard | 2006-04-07 | [kernel: Fixed set\_process\_name for the winevdm case.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fcb771d9c0eafd812432b333cba6f2da0b4e5d8b) |
| Mike McCormack | 2006-04-07 | [shdocvw: Implement IEWinMain using a simple window frame.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5d0873a74c314088426ea3e57fd2496c2d9fa78d) |
| Mike McCormack | 2006-04-06 | [shdocvw: Forward IWebBrowser2::Navigate calls to ::Navigate2.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ba881a94d8ff29e20c9c8763a517001075a63bb8) |
| Alexandre Julliard | 2006-04-06 | [kernel: Show the exe name instead of wine-[kp](http://source.winehq.org/git/wine.git?a=commitdiff;h=9603ee07565d1ab8ae2f272094fcebab982933d9)thread in ps and top.] |
| Mike McCormack | 2006-04-05 | [shdocvw: Add class definition for InternetExplorer.](http://source.winehq.org/git/wine.git?a=commitdiff;h=152541b94c48c03c528659835482ad30f48b09fb) |
| Mike McCormack | 2006-04-04 | [shdocvw: Stub implementation of IEWinMain.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fc33d3bca8fb2c87500ac4144d64c6621f7e3eca) |
| Mike McCormack | 2006-04-04 | [Add an implementation of iexplore.exe.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5a5b35cec791c7616595f04e67b73e44483a6a9e) |
| Dmitry Timoshkov | 2006-04-03 | [gdi: Move WineEngInit call before stock fonts creation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fd2ed6fffe495e243ce4480315f7bdb19d2a59e3) |
| Alexandre Julliard | 2006-03-31 | [loader: Hide the preloader from the ps output.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c20d6c409569a916231d14acd8a5a104cfedf74b) |
| Mike McCormack | 2006-03-30 | [WININET: Clean up HttpQueryInfo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ae300883faa29ddad5c65aeac5cad682380e4cd3) |
| Mike McCormack | 2006-03-30 | [wininet: Clean up HTTP\_GetCustomHeaderIndex.](http://source.winehq.org/git/wine.git?a=commitdiff;h=92ddc1c851a01773221d3863dbad38a344630b0a) |
| Mike McCormack | 2006-03-30 | [wininet: Use a lookup table sorted by index so we don't need a loop to do lookups.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7f5e273214bb4d75824efc7133b366b4703450a6) |
| Mike McCormack | 2006-03-30 | [wininet: Make sure to set LastError when returning FALSE in HttpQueryInfo.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2571fa004a334818c1d9c0a438c974a9ce28106f) |
| Mike McCormack | 2006-03-28 | [server: Fix a race condition in the delivery of change notifications.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f5c1381e065bfab1903eebd7596f670b82c28509) |
| Alexandre Julliard | 2006-03-28 | [x11drv: Only warp the mouse pointer if it has actually moved.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bc15e1bc8195737e0f9ddc741cf4d9e79f500c55) |
| Alexandre Julliard | 2006-03-28 | [mshtml: Don't free the URL we have just stored in the callback object.](http://source.winehq.org/git/wine.git?a=commitdiff;h=31332b3cd6d1c8fb0e11cbb2ff7d00a223468a8f) |
| Alexandre Julliard | 2006-03-27 | [server: Store window properties in the global atom table instead of](http://source.winehq.org/git/wine.git?a=commitdiff;h=641e9e382f8b8ae04296eb94673066e5e5566170) |
| Jacek Caban | 2006-03-27 | [mshtml: Added tooltip implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5f009f2540759d767f4fa696d855edfd21bc3dcd) |
| Mike McCormack | 2006-03-24 | [ntdll: Recursive notify is implemented.](http://source.winehq.org/git/wine.git?a=commitdiff;h=23b74754fed40211550e5a6e224880a737107ad8) |
| Jacek Caban | 2006-03-23 | [mshtml: Added IHTMLElement2 implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ed10e5046c107971bd689b3c1564106d9ee6afce) |
| Jacek Caban | 2006-03-23 | [exdisp.idl: Added missing IE6 methods to DWebBrowserEvents2.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9c2254468879430bb52aac5255c58ecf62a170b6) |
| Jacek Caban | 2006-03-22 | [mshtml: Clean up get\_all and tags (also fixes a typo).](http://source.winehq.org/git/wine.git?a=commitdiff;h=b88b981dcbb0b220ef1686a3acde2658c995c7fd) |
| Alexandre Julliard | 2006-03-22 | [server: New scheme for cleaning up objects on server exit.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b00fb174f6b8ae8940f37c1229040a3cca84de74) |
| Alexandre Julliard | 2006-03-22 | [server: Class and global atoms should not be local to a window station.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9873494ced8405113381266b4d99c2a9f3002cb1) |
| Aric Stewart | 2006-03-22 | [twain: Add a property sheet UI for scanning.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8358c63e15b64f7e11a238e2b375121108148479) |
| Aric Stewart | 2006-03-22 | [twain: A few cleanups, using some consts from sane.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0bcc992162a5ce4a338c9210ef90e6a98dcf3254) |
| Alexandre Julliard | 2006-03-20 | [x11drv: Clear new bitmaps if they don't contain any data.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ddc60c85f6747a96c93925b2fd785d1419f17dee) |
| Alexandre Julliard | 2006-03-20 | [configure: Use --rpath when linking dlls too.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1fd32cfa137867081f3a1ebf5a22b059e4c6dc83) |
| Alexandre Julliard | 2006-03-20 | [kernel: Avoid infinite waits in directory change tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=13c2f4742f776e40815287fce2d78cee1e8c265b) |
| Jacek Caban | 2006-03-18 | [mshtml: Optimize nsACString handling.](http://source.winehq.org/git/wine.git?a=commitdiff;h=dbd582cf8423c2c3cb723386df37c89a59e45789) |
| Jacek Caban | 2006-03-18 | [mshtml: Better QueryInterface implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3d9d3844860efc63590fa2df44605e543a9fa7bf) |
| Jacek Caban | 2006-03-18 | [mshtml.idl: Added more interfaces.](http://source.winehq.org/git/wine.git?a=commitdiff;h=144bb464c3089456fc19a1580dfa1898ccafb20c) |
| Alexandre Julliard | 2006-03-10 | [aclocal.m4: Avoid invalid characters in the cache variable name in WINE\_GET\_SONAME.](http://source.winehq.org/git/wine.git?a=commitdiff;h=30de3e8efe9211d6909a15610725cc8da5eeff70) |
| Alexandre Julliard | 2006-03-10 | [winefile: Refresh the drives and files upon WM\_DEVICECHANGE.](http://source.winehq.org/git/wine.git?a=commitdiff;h=04dad6218f64776712653ecdc24126a4d61f0d59) |
| Alexandre Julliard | 2006-03-09 | [user: Support packing/unpacking the WM\_DEVICECHANGE message.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a32b3e86ec3c6b83804d896ed1cc3438cd9dc482) |
| Jacek Caban | 2006-03-09 | [mshtml: Added beginning of getAttribute implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2c06b800b196887c287b6b2babb09edd989ec598) |
| Alexandre Julliard | 2006-03-09 | [dbt.h: Added DBTF\_ flags.](http://source.winehq.org/git/wine.git?a=commitdiff;h=18345170fd888ef54902bd8f80595bec3dc12f0c) |
| Jacek Caban | 2006-03-08 | [mshtml: Added IHTMLBodyElement implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=26b9c5e022f0ea05b903f7f3583c9ef2a6f64132) |
| Alexandre Julliard | 2006-03-07 | [explorer: Added desktop option.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a93b6a5945b2ffd29cc950fe8e8d6cd6cdf73261) |
| Jacek Caban | 2006-03-07 | [mshtml: Added get\_type, get\_value, get\_name and get\_checked](http://source.winehq.org/git/wine.git?a=commitdiff;h=92ff0e5019bbf6d052c496fb34b64e2e6976c7dd) |
| Jacek Caban | 2006-03-07 | [mshtml: Added get\_name and get\_value implementation of IHTMLTextAreaElement interface.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6fafc22930e6ecc8978ca249ccbff9335fdcfdce) |
| Alexandre Julliard | 2006-03-07 | [explorer: Merged systray support with the desktop window main loop.](http://source.winehq.org/git/wine.git?a=commitdiff;h=576e3b706299f21897fc09c15b767fd79e701e79) |
| Jacek Caban | 2006-03-07 | [mshtml: Added get\_name and get\_value implementation of IHTMLSelectElement interface.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4ac4246fd5435b02b042588bc1cbed4ef796bb9e) |
| Alexandre Julliard | 2006-03-07 | [server: Fixed length check in dump\_inline\_unicode\_string.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3d531f1bb5b54c46eeedc794b29b4458a281d02a) |
| Alexandre Julliard | 2006-03-07 | [user: Launch explorer to manage the desktop window.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1a4f6e579b6aab685fae2e649fd5accee7ec0b4f) |
| Alexandre Julliard | 2006-03-07 | [x11drv: Don't send an invalid WM\_NCCREATE to the desktop window.](http://source.winehq.org/git/wine.git?a=commitdiff;h=116aaa169479a5e42aee6adcf3cf7b4d87beb18d) |
| Alexandre Julliard | 2006-03-06 | [server: Support for closing the desktop window.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f978f615d8d89f5e3dc7056cfff7b34e1f174295) |
| Alexandre Julliard | 2006-03-06 | [user: Allow creating windows of the desktop class.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f874d20f54607dca0113e899c61af0bdaee9adba) |
| Alexandre Julliard | 2006-03-06 | [shell32: Fixed handling of null-terminated file list in SHFileOperation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b222001defc8d9db67232aae68f2d3a83c4ecd5d) |
| Alexandre Julliard | 2006-03-06 | [kernel: Better support for detached processes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a401f3c4bb5819e6fcfefa9587eca60796531c4a) |
| Jacek Caban | 2006-03-06 | [mshtml: Added IHTMLTextAreaElement implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8f897239c46dabeeeb06827f53463e651ee70648) |
| Alexandre Julliard | 2006-03-06 | [server: Added unlink\_named\_object function.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8cea993033944e927e6bcbceda647322d00916e5) |
| Jacek Caban | 2006-03-06 | [mshtml: Added IHTMLInputElement implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8b3eab6e35cf038330880426d0dd2e324db6721f) |
| Jacek Caban | 2006-03-06 | [shdocvw: Added get\_LocationURL implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=87e04f2f4a020a4209f051c2ee39f4c0a463d985) |
| Alexandre Julliard | 2006-03-06 | [server: Avoid crash in set\_thread\_desktop if the thread doesn't have a queue.](http://source.winehq.org/git/wine.git?a=commitdiff;h=71b94726d9661d2f51afe4bd72539de656dcd0a3) |
| Alexandre Julliard | 2006-03-06 | [user: Allow some Wine internal messages to act on the desktop window.](http://source.winehq.org/git/wine.git?a=commitdiff;h=70d42f9d43dbadfdc1692ef574acc7e9b8ee01f2) |
| Alexandre Julliard | 2006-03-06 | [x11drv: Make sure to never manipulate the root window, even if we own](http://source.winehq.org/git/wine.git?a=commitdiff;h=6d5f5447eaae4837d8da9210d21fd3265a0073d7) |
| Jacek Caban | 2006-03-06 | [mshtml: Added IHTMLSelectElement implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=54cce2e7ceccbea268718ea51aea98bac7997627) |
| Alexandre Julliard | 2006-03-06 | [server: Return real parent and owner in the create\_window request.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4be3d4c12b916d2f17c22f09bcf087f7b8ce7390) |
| Jacek Caban | 2006-03-06 | [mshtml: Added IHTMLElementCollection::tags implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3d6859935599321270d6c18a12e3767044963e54) |
| Alexandre Julliard | 2006-03-06 | [libwine: Export a function to retrieve the data directory (based on a](http://source.winehq.org/git/wine.git?a=commitdiff;h=2f026d1694d6e34b6e2d9d4d61ef5632e6f3251d) |
| Alexandre Julliard | 2006-03-06 | [server: Infrastructure for having a thread own the desktop window.](http://source.winehq.org/git/wine.git?a=commitdiff;h=251be542aca1dbf418e5c15e4adb0c5a2d7d3fc0) |
| Alexandre Julliard | 2006-03-06 | [shell32: Store only the file attributes in the file list for SHFileOperation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=23cb632be2265cf9f927cae54237c78dea161358) |
| Alexandre Julliard | 2006-03-06 | [mlang: Decrement the module refcount when an object is destroyed.](http://source.winehq.org/git/wine.git?a=commitdiff;h=19a3adb9580ccf32c66c0ff4864a68d31044684f) |
| Alexandre Julliard | 2006-03-06 | [shell32: Grow the file list dynamically in SHFileOperation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1110d62752947c82723d1eb252be8e49cac3dfb0) |
| Jacek Caban | 2006-03-05 | [mshtml: Added more interfaces to mshtml.idl.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ee1e7e503fb641b4bb21c2561111ca081f7e1475) |
| Jacek Caban | 2006-03-05 | [mshtml: Added IHTMLElementCollection implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d6d76870cb1ccb83f6feb8736dfca6d9dc1d984d) |
| Jacek Caban | 2006-03-05 | [mshtml: Added IHTMLElement implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=874fd57841f8d9670c50429b8b28d6b3627b0bb3) |
| Jacek Caban | 2006-03-05 | [shdocvw: Beginning ShowContextMenu implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7a3a554c9b4aa3a894864a7c3f3eef6bac053eb6) |
| Jacek Caban | 2006-03-05 | [mshtml: Added get\_documentElement implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6ef5f9556215ac4b3426028cc7156eaa133d20ef) |
| Jacek Caban | 2006-03-05 | [mshtml: Added IHTMLDOMNode implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=54036bf6efa06337f5d8649037246f6a75ec652d) |
| Dmitry Timoshkov | 2006-03-04 | [winebrowser: Use CP\_UNIXCP when translating URL passed on command line](http://source.winehq.org/git/wine.git?a=commitdiff;h=182a66c0db3a9fa45c032f82f45ff155e3120ff5) |
| Aric Stewart | 2006-03-03 | [shell32: Skip dot directories in SHFileOperation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c29b7c352438669ee22961466360e926a831d313) |
| Huw Davies | 2006-03-02 | [gdi: Better support for 1bpp dib sections.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b55746ab62739fc1e4c0d4a15484e0e8337bab75) |
| Jacek Caban | 2006-03-01 | [mshtml: Beginning support for links opened in a new frame.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d656f996f118667a9a455c08a950d4f4ab647a0b) |
| Jacek Caban | 2006-03-01 | [shdocvw: Don't call hlink\_navigate if HLNF\_OPENINNEWWINDOW is set.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d3a5921e8eeaab5f33bb074c77bb04d8ccd0fa0a) |
| Jacek Caban | 2006-03-01 | [mshtml: Use NSContainer as 'This' of its window.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2be7ffdf594594f74a702ebc67a8bf4746bf6bd3) |
| Alexandre Julliard | 2006-02-28 | [wrc: Integer ids can be used for control labels instead of strings.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8f08fe6c0dc9ad3f2d5e00f2b79488eba622cd26) |
| Dmitry Timoshkov | 2006-02-28 | [notepad: Wrap long lines by default like Windows does.](http://source.winehq.org/git/wine.git?a=commitdiff;h=832ec7056511ee04dc3d4fdce09acf2ceb2c58dd) |
| Mike McCormack | 2006-02-28 | [server: Print a message if wineserver crashes and we don't dump cores.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0cd0626de019c8ca288ed8a61a053c0f485c5c5c) |
| Jacek Caban | 2006-02-27 | [mshtml: Added nsIInterfaceRequestor implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=91369e20e756313f586de03da1354b4f621985fe) |
| Jacek Caban | 2006-02-24 | [mshtml: Return error in NewChannelFromURL if retval is NULL.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b7e8057eecc14d38d41b9b28cb52c77557655330) |
| Jacek Caban | 2006-02-24 | [mshtml: Improve ConfirmEx hack.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a611b20c2621d4fccfa2b07d4ee357035b10e8db) |
| Jacek Caban | 2006-02-24 | [mshtml: Added nsIURI::Clone implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9b6c08a243c374bdd6dd58fcec5d6e72b2300bb9) |
| Jacek Caban | 2006-02-24 | [mshtml: Don't add null byte to post data.](http://source.winehq.org/git/wine.git?a=commitdiff;h=71b881e4ba75bd2cccde863e55cdd4189d946c35) |
| Jacek Caban | 2006-02-24 | [mshtml: Init nsIOService as soon as possible.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4f9c9a16ad24af79a0de60053290bc210c1f3e00) |
| Dmitry Timoshkov | 2006-02-23 | [gdi: Use &quot;MS Sans Serif&quot; as default sans serif font, not Arial.](http://source.winehq.org/git/wine.git?a=commitdiff;h=69a23a608eea59624b2f37ab424e0f42b3da5baf) |
| Huw Davies | 2006-02-23 | [gdi32: Fallback to StretchDIBits if the driver doesn't support BitBlt.](http://source.winehq.org/git/wine.git?a=commitdiff;h=66a05b2aec118946d75f159237a3c73df38f2486) |
| Mike McCormack | 2006-02-22 | [server: Add directories to recursive watches as they're opened.](http://source.winehq.org/git/wine.git?a=commitdiff;h=42121085985b3995692c4b40ee1b127963785223) |
| Mike McCormack | 2006-02-22 | [server: Make sure we don't get into an infinite loop freeing inodes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=309a9bf36fa114ad59b61987cf27b4f39faf7125) |
| Mike McCormack | 2006-02-21 | [kernel32: Add a short test for GetOverlappedResult.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f4b447aee7546c9921dd3a9c8d81ccdc6b1b1fae) |
| Mike McCormack | 2006-02-21 | [server: Track created and removed directories in the tree of inodes for inotify.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e4faabfa64aa0c89db482fc780ed1a7f51efa53e) |
| Aric Stewart | 2006-02-21 | [twain: Implment DG\_IMAGE/DAT\_IMAGEMEMXFER/MSG\_GET.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6976e2016d28249988ed975657f704fb5682b715) |
| Mike McCormack | 2006-02-21 | [kernel32: Add a simple test for recursive notification.](http://source.winehq.org/git/wine.git?a=commitdiff;h=54dfdb9b006fcd310a73d1e6bdf388cecd6c13d1) |
| Alexandre Julliard | 2006-02-21 | [server: Avoid hang on process startup.](http://source.winehq.org/git/wine.git?a=commitdiff;h=492661079c01313ad46797c984a09a2010d3ebe5) |
| Alexandre Julliard | 2006-02-21 | [shell32: Use more reasonable timeouts in shlexec test.](http://source.winehq.org/git/wine.git?a=commitdiff;h=39a1a9422149a0d3d081f02d540423eac131bfaa) |
| Jacek Caban | 2006-02-21 | [shdocvw: Added correct implementation of IProvideClassInfo::GetGUID.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0c12e2663b6964d1cfc44b5546800e42452aba3b) |
| Mike McCormack | 2006-02-20 | [server: Distinguish between a directory and a file changing in](http://source.winehq.org/git/wine.git?a=commitdiff;h=a2813f7c2ef879fee94948eb4f935448e2f48152) |
| Jacek Caban | 2006-02-20 | [mshtml: Create nsIChannel for protocols not handled by Gecko.](http://source.winehq.org/git/wine.git?a=commitdiff;h=746616903481155b576c201ed734ebe9a61a82a7) |
| Alexandre Julliard | 2006-02-20 | [configure: Use --rpath if supported when building binaries to point to](http://source.winehq.org/git/wine.git?a=commitdiff;h=5ed59015b290c7c1238c7d08cacc299f0aa151e2) |
| Jacek Caban | 2006-02-20 | [mshtml: Set default original uri in NewChannelFromURI.](http://source.winehq.org/git/wine.git?a=commitdiff;h=416f504cdd340b8f75ea396245e7c1dad6499cbb) |
| Jacek Caban | 2006-02-20 | [shdocvw: Change FIXMEs to TRACE in IDispatch's methods as they return](http://source.winehq.org/git/wine.git?a=commitdiff;h=00f249022cdc6ae6ec04be17dfafecb38c34ab74) |
| Mike McCormack | 2006-02-17 | [server: Use a single inotify watch, as it scales better with a large](http://source.winehq.org/git/wine.git?a=commitdiff;h=fbc00db3f6cc2cf2434aa7063039df95329c64f2) |
| Alexandre Julliard | 2006-02-17 | [libwine: Set the default bindir and dlldir from argv0 if dladdr is not available.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e95a2c2111add8d40d486846fae844715577ef56) |
| Alexandre Julliard | 2006-02-17 | [ntdll: Remove no longer used oldcwd in start\_server.](http://source.winehq.org/git/wine.git?a=commitdiff;h=dcdb0d0b34a4f4d545bd307d0ff041eec3555220) |
| Jacek Caban | 2006-02-17 | [mshtml: Fix post data parsing.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d2389dc0cf16511266884df583f5d86fd5357cf0) |
| Alexandre Julliard | 2006-02-17 | [libwine: Compute relative paths for bin and dll directories at compile time.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8b5e11c341c11b3a417d5845d8ff11aca77b339d) |
| Alexandre Julliard | 2006-02-17 | [tools: Added 'relpath' tool to compute relative Unix paths.](http://source.winehq.org/git/wine.git?a=commitdiff;h=35842ca71763682dbae233115a1ab7004bf8cf8d) |
| Alexandre Julliard | 2006-02-17 | [libwine: Add the runtime library path to the front of the dll paths list.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1269f43c5a68e03b526098fb18dd0edd42858ceb) |
| Alexandre Julliard | 2006-02-16 | [libwine: Only use the library directory if it's an absolute path.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ca6fd0d4eceae51f816457f425111a811d6ef057) |
| Thomas Kho | 2006-02-16 | [riched20: Implement EM\_SCROLLCARET and EM\_GETSCROLLPOS.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bfb3c756eb5f956904e5f3154eb09be34aa63e94) |
| Alexandre Julliard | 2006-02-16 | [libwine: Try the current load path in priority before the](http://source.winehq.org/git/wine.git?a=commitdiff;h=9dffd134ddcab7d87f2507e3bc37a8ee8029f5dc) |
| Juan Lang | 2006-02-16 | [wininet: Use CertNameToStr for INTERNET\_OPTION\_SECURITY\_CERTIFICATE\_STRUCT](http://source.winehq.org/git/wine.git?a=commitdiff;h=89529f8a8ebcdf63fb176e853a59158cbdf39da4) |
| Jacek Caban | 2006-02-16 | [shdocvw: Unaccess post data only if we've accessed it before.](http://source.winehq.org/git/wine.git?a=commitdiff;h=76a361af8215fa8f8be741c14afad84ae3f1770f) |
| Alexandre Julliard | 2006-02-16 | [libwine: Don't rely on argv[0](http://source.winehq.org/git/wine.git?a=commitdiff;h=767ad69a456f4ba2e35d297069188a0e5773a62c) in wine\_exec\_wine\_binary if we can get] |
| Jacek Caban | 2006-02-15 | [shdocvw: Added beginning IHlinkFrame::Navigate implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f98843e8cc5b165dbc724bf8213e2827ad65ca94) |
| Jacek Caban | 2006-02-15 | [shdocvw: Added client site's IServiceProvider interface.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ad5d88c67a7999ef380e48e5ea1011217e192a0a) |
| Jacek Caban | 2006-02-15 | [mshtml: Added hack to allow pass post data to IPersistMoniker::Load.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4b511edf8d5ab2a0ab0fe08d762ec2ded445bcd0) |
| Jacek Caban | 2006-02-15 | [mshtml: Added ref counting to NSContainer.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4acea60922128283e2b10f2e202fb428206b3abc) |
| Jacek Caban | 2006-02-15 | [shdocvw: Navigate2 rewrite.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0dbbd90c6a8346569316fc00b07d4817556167d4) |
| Juan Lang | 2006-02-15 | [crypt32: Output string type in trace.](http://source.winehq.org/git/wine.git?a=commitdiff;h=09b6cf971ff1de7574dcb7c18d297cab34bb7922) |
| Thomas Kho | 2006-02-15 | [riched20: Extend EM\_FINDTEXT conformance tests and fix 2 problems they expose.](http://source.winehq.org/git/wine.git?a=commitdiff;h=087af502ea547d4fa804bca688e00cb351ed13f7) |
| Dmitry Timoshkov | 2006-02-14 | [winmm: Protect drivers list by a critical section.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f29d4af34b4ef88838d545788de0d5f107ff6375) |
| Dmitry Timoshkov | 2006-02-14 | [msvfw32: Disable datarate, keyframe and quality controls to not](http://source.winehq.org/git/wine.git?a=commitdiff;h=f1e120ba7ea514fbf8c916e7608f9f165fb84135) |
| Jeremy White | 2006-02-14 | [twain: Reconcile sane's long names to TWAIN's 32 byte limit.](http://source.winehq.org/git/wine.git?a=commitdiff;h=63e8d34a42f717897635fa1d6bc39fb805bc1ff2) |
| Dmitry Timoshkov | 2006-02-14 | [msvfw32: Initialize lpbiIn member of the COMPVARS structure.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5de3d7df3266f7888be7164f29654dc80511ee24) |
| Jeremy White | 2006-02-14 | [twain: Make structures respect 2 byte packing requirements.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5b04c3ea5aaf514a66bf5d06a606b3ec2b9ac1e7) |
| Dmitry Timoshkov | 2006-02-13 | [msvfw32: Fix typos in the control state handling.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d4774ba1c66e9f4acabf977ecfb1d763e30eaa1f) |
| Jacek Caban | 2006-02-13 | [mshtml: Handle IHlinkFrame service.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cb880d7cc70f48804e052a3cd45d1e7804daa951) |
| Dmitry Timoshkov | 2006-02-11 | [msvcrt: localtime should accept any positive time value.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ea0e7b339751c16dca08c73cfc292a843f641bda) |
| Thomas Kho | 2006-02-11 | [riched20: Fixed bounds error when finding text forward.](http://source.winehq.org/git/wine.git?a=commitdiff;h=caffa53227d37f35bc32c03733dfc94556ff513f) |
| Dmitry Timoshkov | 2006-02-11 | [msvfw32: Call codec's Configure dialog if the codec supports it.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cad998112ece02f9a768083462c60832f1cfcbb6) |
| Dmitry Timoshkov | 2006-02-11 | [Handle ICM\_CONFIGURE request in ICCVID and MSVIDC32 codecs.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b4b3e6a165723b965af7b8352932ddf91fc404e8) |
| Thomas Kho | 2006-02-11 | [riched20: Added tests for EM\_FINDTEXT and EM\_FINDTEXTEX messages.](http://source.winehq.org/git/wine.git?a=commitdiff;h=482ab27e8d3cf6414d4db7c940328d07e14776f4) |
| Alexandre Julliard | 2006-02-11 | [configure: Added a WINE\_CHECK\_LIB\_FUNCS macro to check for functions](http://source.winehq.org/git/wine.git?a=commitdiff;h=2d1a6274ee8c8fc8ac33f5ed53892711492321db) |
| Alexandre Julliard | 2006-02-11 | [configure: Added check for dladdr in libdl.](http://source.winehq.org/git/wine.git?a=commitdiff;h=266c609dd1dab8caab71ea1cc3949dacfcde8c40) |
| Alexandre Julliard | 2006-02-11 | [libwine: Use dladdr if supported to get the run-time path of libwine.so](http://source.winehq.org/git/wine.git?a=commitdiff;h=0b34fb365657b9983a591610b2d80e298623d6f0) |
| Aric Stewart | 2006-02-10 | [ntdll: gcc 2.95 compile fixes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d7187d79bdaa616332b33ef4acb3d8144e2dc9f8) |
| Jacek Caban | 2006-02-10 | [mshtml: Added nsIUploadStream implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=af6395774c10b4e7932e3044af5ce9dbf380b046) |
| Jacek Caban | 2006-02-10 | [mshtml: Added more defines to mshtmlhst.idl.](http://source.winehq.org/git/wine.git?a=commitdiff;h=adb1335e4e458968dbce03e087c66d51783e91cf) |
| Jacek Caban | 2006-02-10 | [mshtml: Added test of IHlinkFrame service.](http://source.winehq.org/git/wine.git?a=commitdiff;h=4a34d8e6424a5174ab52c657fc9ab5d8c8995465) |
| Jacek Caban | 2006-02-09 | [mshtml: Added wrapper of nsIChannel.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ae23f8d8cbac12d984394bfd446b0118ecdb29fd) |
| Jacek Caban | 2006-02-09 | [mshtml: Get rid of HTMLDocument\_OnLoad and move its job to AsyncOpen.](http://source.winehq.org/git/wine.git?a=commitdiff;h=990e20c9922d4b058242f4eb7b9da845af8d38de) |
| Aric Stewart | 2006-02-09 | [advapi32: Fix for RegNotifyChangeKeyValue.](http://source.winehq.org/git/wine.git?a=commitdiff;h=910806393dbffc77094652cb7dfff93217e3e4eb) |
| Jacek Caban | 2006-02-09 | [mshtml: Added wrapper of nsIOService.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8aeb04934122dd0d4878a537ea0bf3da481515a1) |
| Jacek Caban | 2006-02-09 | [mshtml: Better ns\*String handling.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7080c8d98ebc46fef3bedcb457e0be4643616a3d) |
| Juan Lang | 2006-02-09 | [crypt32: Fix up decoding.](http://source.winehq.org/git/wine.git?a=commitdiff;h=69698f9b44ce78b6e60e91e9664779e8a0e5383b) |
| Dmitry Timoshkov | 2006-02-09 | [regsvr32: Call OleInitialize before registering a DLL.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2c59936fee254cfae4c646fccb3a6cc3f3c92f27) |
| Jacek Caban | 2006-02-09 | [mshtml: Added wrapper of nsIURI interface.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1b31475fdb2b9a46b557225d319a93671d895458) |
| Juan Lang | 2006-02-09 | [crypt32: Fix a fixme, and remove an old comment.](http://source.winehq.org/git/wine.git?a=commitdiff;h=02c4956157033896077b4027834f11f8dcdb56f3) |
| Jacek Caban | 2006-02-08 | [shdocvw: Remove IQuickActivate interface implementation that is not](http://source.winehq.org/git/wine.git?a=commitdiff;h=fa31cfb0b31c19839bd13b05a9d2d2e7a6b9b3b7) |
| Alexandre Julliard | 2006-02-08 | [server: Fixed handling of inotify record length.](http://source.winehq.org/git/wine.git?a=commitdiff;h=e979832dda71deeea092c31046f543fbeec13c5c) |
| Jacek Caban | 2006-02-08 | [shdocvw: Includes clean up.](http://source.winehq.org/git/wine.git?a=commitdiff;h=5d854158b8c9d67968802a3b27bd8407dce2b28c) |
| Jacek Caban | 2006-02-08 | [shdocvw: Added IHlinkFrame stub implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=461a0102c53e0d5704d5a0d949a90f70841cc1fd) |
| Jacek Caban | 2006-02-08 | [urlmon.idl: Added BINDINFOF declaration.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0e3be46855c44fe4d2dbde42c0cca53be9b2d8c4) |
| Mike McCormack | 2006-02-07 | [kernel32: More test cases for ReadDirectoryChangesW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=7a61f086f17057a19ad3a65e2f177bbe3de136ac) |
| Dmitry Timoshkov | 2006-02-07 | [msvideo: Add a codec to the compressors list only if it supports](http://source.winehq.org/git/wine.git?a=commitdiff;h=75c436246d7eaf3d268a30e7401d289e6dd6e399) |
| Dmitry Timoshkov | 2006-02-07 | [x11drv: Copy the whole image at once if appropriate.](http://source.winehq.org/git/wine.git?a=commitdiff;h=729eaa6920a672acc0d8b682bcc9336b8575a364) |
| Dmitry Timoshkov | 2006-02-07 | [Clearly indicate that ICCVID and MSVIDC32 do not support compression.](http://source.winehq.org/git/wine.git?a=commitdiff;h=538ed06c41521fa8f884ecf39a7e617fafb43bc1) |
| Mike McCormack | 2006-02-07 | [kernel32: ReadDirectoryChangesW fixes.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0790f955897d5664997d7263fbd3e42165eda548) |
| Mike McCormack | 2006-02-06 | [ntdll: Add some more tests for NtNotifyChangeDirectoryFile.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bad5f92f540da2e7da9d1dad77a12b6a3e860b35) |
| Mike McCormack | 2006-02-06 | [server: Fill in NtNotifyChangeDirectoryFile's buffer with change data.](http://source.winehq.org/git/wine.git?a=commitdiff;h=01932119464a2a97421daeee1cdd8200646a67a1) |
| Alexandre Julliard | 2006-02-05 | [server: Fixed compile without inotify.](http://source.winehq.org/git/wine.git?a=commitdiff;h=cf9ced5e691ccaf76bc87f5171239fd5fe838d85) |
| Dmitry Timoshkov | 2006-02-04 | [msvfw32: Do not overwrite fccType in the codec enumeration proc.](http://source.winehq.org/git/wine.git?a=commitdiff;h=3f2e9681a60f87a5489bc5d5595f9a6496b5e013) |
| Dmitry Timoshkov | 2006-02-03 | [wine.inf: Change fcc type of builtin video codecs in system.ini to be](http://source.winehq.org/git/wine.git?a=commitdiff;h=de60d1e3bc616db9cb02b65346ecfcd592b659a7) |
| Dmitry Timoshkov | 2006-02-03 | [Add support for CDM\_HIDECONTROL message in the file open dialog.](http://source.winehq.org/git/wine.git?a=commitdiff;h=c8c8f1b8badf601bc4f9c8551573b5ca9b7f9540) |
| Dmitry Timoshkov | 2006-02-03 | [Add a check for icinfo-&gt;fccType in DRV\_OPEN message handler of builtin](http://source.winehq.org/git/wine.git?a=commitdiff;h=c13ae562892841a680ee68d965c8deadc47c15b2) |
| Mike McCormack | 2006-02-03 | [ntdll: Add FILE\_ACTION and FILE\_NOTIFY\_CHANGE\_ defines for streams.](http://source.winehq.org/git/wine.git?a=commitdiff;h=39f711ae6ec107c4a12ac900df574e79c161873b) |
| Alexandre Julliard | 2006-02-03 | [wine.inf: Make FourCC codes uppercase again until we can figure out](http://source.winehq.org/git/wine.git?a=commitdiff;h=19b89289ee077f7cc56148f05c6aff4549af234b) |
| Juan Lang | 2006-02-02 | [crypt32: Implement CertRDNValueToStrW and CertNameToStrW, with tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ede2e24a6af7677217486cc2f213dfebac15314a) |
| Mike McCormack | 2006-02-02 | [kernel32: FindFirstChangeNotification needs a static IO\_STATUS\_BLOCK.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d77baf358b2ba376d68ed9f590fe1d413e9f12c9) |
| Dmitry Timoshkov | 2006-02-01 | [wine.inf: Remove %1 from [http|htmlfile](http://source.winehq.org/git/wine.git?a=commitdiff;h=f03c86a27387cd1dc27c371d52a7c72d83b70481)\shell\open\command.] |
| Juan Lang | 2006-02-01 | [crypt32: Implement CertRDNValueToStrA and CertNameToStrA, with tests.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6a3b3f8635669ddf6fdae8d2d6a1b7c1a9ab3771) |
| Mike McCormack | 2006-01-31 | [kernel: Add some test cases for ReadDirectoryChangesW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9e2b6687f6ec1bbda1af684571ea9a7a9b7c6223) |
| Alexandre Julliard | 2006-01-31 | [kernel: Set the overlapped structure status in ReadDirectoryChanges.](http://source.winehq.org/git/wine.git?a=commitdiff;h=096000df90fbd047bd7893fbd344572514167d9b) |
| Mike McCormack | 2006-01-30 | [server: Initial inotify support.](http://source.winehq.org/git/wine.git?a=commitdiff;h=fdf0c684f56d8d679def550b92875fcddd219d9e) |
| Mike McCormack | 2006-01-30 | [kernel: Add some more tests for FindFirstChangeNotification.](http://source.winehq.org/git/wine.git?a=commitdiff;h=bd185ff3de84edf0ff38bb1ba18d34a1b9969b8c) |
| Alexandre Julliard | 2006-01-30 | [Fixed creation of PS\_ALTERNATE pens.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6b76244bf42a82f523f1c6c22607187dc1ce9c7d) |
| Alexandre Julliard | 2006-01-27 | [shell32: Fixed a couple of FindFirstFile handle leaks.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d37a119ee66ad43099791605a748013ec69c7e2f) |
| Alexandre Julliard | 2006-01-27 | [server: Make the FILE\_SHARE\_DELETE sharing checks depend on DELETE](http://source.winehq.org/git/wine.git?a=commitdiff;h=8b0feb253bc569a39e724a8da006735166fc1b32) |
| Mike McCormack | 2006-01-27 | [kernel: Partially implement ReadDirectoryChangesW using NtNotifyChangeDirectoryFile.](http://source.winehq.org/git/wine.git?a=commitdiff;h=700575955782bed874734610476aab6c8826f775) |
| Alexandre Julliard | 2006-01-27 | [server: Fixed low-level hardware hooks.](http://source.winehq.org/git/wine.git?a=commitdiff;h=6d85f3bf218faa25012d7d2f5b1c2aaa52f67631) |
| Mike McCormack | 2006-01-27 | [kernel32: Implement FindFirstChangeNotification with NtNotifyChangeDirectoryFile.](http://source.winehq.org/git/wine.git?a=commitdiff;h=53dab1520055b089f1b40d3164245b7890843294) |
| Mike McCormack | 2006-01-27 | [server: Fix the file notification interface to use directory handles.](http://source.winehq.org/git/wine.git?a=commitdiff;h=08351071fd304748c86de4d6285f7ef5b8f0bd17) |
| Jacek Caban | 2006-01-26 | [shdocvw: Added client site's IOleCommandTarget stub implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=254bdf08f147720d8d5305423652b7cf5f7d7624) |
| Jacek Caban | 2006-01-26 | [shdocvw: Added WebBrowser's IOleCommandTarget stub implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=1b966122f85817195f3d32c1cf03d33e7f6abafb) |
| Jacek Caban | 2006-01-26 | [shdocvw: Added client site's IDispatch stub implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0e1ef8ac2ef68faee2d35ff8a4e3dc6dbd054899) |
| Alexandre Julliard | 2006-01-25 | [wine.inf: Don't overwrite registry keys that users may want to change.](http://source.winehq.org/git/wine.git?a=commitdiff;h=f8f34d9fabb2be7582158fc74548f092dc2682f3) |
| Jacek Caban | 2006-01-25 | [shdocvw: Store IDocHostUIHandler interface in the WebBrowser object.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9cbe52b111b774c3482973b7fc1363c875c15501) |
| Jacek Caban | 2006-01-25 | [shdocvw: Added TranslateUrl implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=53c469f1e869ff07e80240cf8fb104eebeb10558) |
| Alexandre Julliard | 2006-01-25 | [x11drv: Always set GC function to GXcopy for the BitBlt DIB optimization.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0e08584462afd57c95af2cd4a5afa5a824975a66) |
| Jacek Caban | 2006-01-24 | [Added mshtmcid.h.](http://source.winehq.org/git/wine.git?a=commitdiff;h=ea6e5b969a255733fefc4e37eeaf6a39245ab7e4) |
| Alexandre Julliard | 2006-01-24 | [server: Use the new set\_fd\_user function in create\_serial().](http://source.winehq.org/git/wine.git?a=commitdiff;h=ab5ca5c04829642fbf1cff1a6c530e6fe1afd313) |
| Mike McCormack | 2006-01-24 | [server: Modify open\_fd to create an fd without a user.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9a7124e8159dc9ff3bcb3b04b970264ca77c1a47) |
| Dmitry Timoshkov | 2006-01-23 | [ICCompressorChoose should initialize fccType and fccHandler fields](http://source.winehq.org/git/wine.git?a=commitdiff;h=2a93c2f23defc6a4aec7a7335a5a792dd808011f) |
| Mike McCormack | 2006-01-23 | [ntdll: Forward ZwNotifyChangeDirectoryFile to NtNotifyChangeDirectoryFile.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2735fc58b990a94554e62cd8287fcd63962b65a9) |
| Aric Stewart | 2006-01-20 | [wininet: INTERNET\_OPTION\_SECURITY\_CERTIFICATE\_STRUCT work.](http://source.winehq.org/git/wine.git?a=commitdiff;h=8b0883576ee7c691cc57d68af6f5050fea981827) |
| Jacek Caban | 2006-01-20 | [shdocvw: Added GetWindow implementation.](http://source.winehq.org/git/wine.git?a=commitdiff;h=360a4aff2982a7d34595f25cd2f9f3f7a4caa4d7) |
| Aric Stewart | 2006-01-19 | [shell32: Update shellpaths My Pictures, My Video, My Music to be under](http://source.winehq.org/git/wine.git?a=commitdiff;h=265c8a5d7329a1512db900a799bd66013365b295) |
| Jacek Caban | 2006-01-18 | [shdocvw: Deactivate document in SetClientSite if ClientSite is NULL.](http://source.winehq.org/git/wine.git?a=commitdiff;h=47f796c6293c8a174006b2ab6de1316c407ab29e) |
| Mike McCormack | 2006-01-17 | [ntdll: Use FILE\_OPEN instead of OPEN\_EXISTING when calling NtCreateFile.](http://source.winehq.org/git/wine.git?a=commitdiff;h=9c58884161729aae445e25e15c28b87837f5cbff) |
| Mike McCormack | 2006-01-17 | [ntdll: Add a test for NtNotifyChangeDirectoryFile.](http://source.winehq.org/git/wine.git?a=commitdiff;h=2e32a425db6bcb86804517761686f31169ff3b80) |
| Mike McCormack | 2006-01-17 | [server: Make sure to release the fd we grabbed in all cases.](http://source.winehq.org/git/wine.git?a=commitdiff;h=213e01e606bc0434059fced84b2bcf349e622bcc) |
| Mike McCormack | 2006-01-16 | [kernel32: Add FILE\_NOTIFY\_INFORMATION.](http://source.winehq.org/git/wine.git?a=commitdiff;h=b8e5e0168a70432e6991289643254074b103b42b) |
| Mike McCormack | 2006-01-16 | [ntdll: Use the NTAPI definition of EXCEPTION\_ACCESS\_VIOLATION.](http://source.winehq.org/git/wine.git?a=commitdiff;h=a3348cf4a0179a4d2097d59c27096d5f9d250fe9) |
| Mike McCormack | 2006-01-16 | [ntdll: Add a stub implementation of NtNotifyChangeDirectoryFile.](http://source.winehq.org/git/wine.git?a=commitdiff;h=0c728255a4f0188acf379aa750437b6c3cd11d87) |
| Jacek Caban | 2006-01-14 | [mshtml: Better handling of IDocHostUIHandler in SetClientSite.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d44364d3fe61dca9d7d3f1189e8d24fcbae2336d) |
| Aric Stewart | 2006-01-14 | [explorer: Handle /select arguments correctly with the new winefile](http://source.winehq.org/git/wine.git?a=commitdiff;h=7439c29d07f7259e789f1d6c54c2feb8021441ad) |
| Aric Stewart | 2006-01-13 | [wininet: Handle NULL lpBuffersIn in HttpSendRequestExW.](http://source.winehq.org/git/wine.git?a=commitdiff;h=21712d3d156740b18f2d9489ec819fbda41b3b13) |
| Aric Stewart | 2006-01-11 | [winefile: Highlight the file specified on the command line instead of](http://source.winehq.org/git/wine.git?a=commitdiff;h=59b2838f4ea5c0a542a22bb5f622a1999db51429) |
| Aric Stewart | 2006-01-11 | [msvcrt: Modify dir test to create its own directory to ensure the](http://source.winehq.org/git/wine.git?a=commitdiff;h=4bc3b16b449d0508f16f324e82228d752d4792da) |
| Dan Kegel | 2006-01-05 | [oleaut32: Allow \_invoke to handle up to 23 parameters.](http://source.winehq.org/git/wine.git?a=commitdiff;h=d69366a17191fb96b92aecf085561ad047adfd86) |