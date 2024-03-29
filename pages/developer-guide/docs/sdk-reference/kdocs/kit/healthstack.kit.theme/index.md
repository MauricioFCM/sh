---
title: healthstack.kit.theme
permalink: /kit/healthstack.kit.theme/index.html

sidebar: dev_doc_sidebar
---
//[kit](../../kit.html)/[healthstack.kit.theme](index.html)



# Package healthstack.kit.theme



## Types


| Name | Summary |
|---|---|
| [AppColors](-app-colors/index.html) | [androidJvm]<br>class [AppColors](-app-colors/index.html)(val primary: Color, val primaryVariant: Color, val background: Color, val surface: Color, val onPrimary: Color, val onBackground: Color, val onSurface: Color, val onSurfaceVariant: Color, val error: Color, val errorVariant: Color, val onError: Color, val disabled: Color, val onDisabled: Color, val disabled2: Color, val onDisabled2: Color, val dataVisualization1: Color, val dataVisualization1Variant: Color, val dataVisualization2: Color, val dataVisualization2Variant: Color, val dataVisualization3: Color, val dataVisualization3Variant: Color, val dataVisualization4: Color, val dataVisualization4Variant: Color, val dataVisualization5: Color, val dataVisualization5Variant: Color, val success: Color, val successVariant: Color, val warning: Color, val warningVariant: Color, val isLight: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [AppTheme](-app-theme/index.html) | [androidJvm]<br>object [AppTheme](-app-theme/index.html) |
| [AppTypography](-app-typography/index.html) | [androidJvm]<br>data class [AppTypography](-app-typography/index.html)(val headline1: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 40.sp,         lineHeight = 52.sp     ), val headline2: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 32.sp,         lineHeight = 41.6.sp     ), val headline3: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 20.sp,         lineHeight = 26.sp     ), val headline4: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 16.sp,         lineHeight = 20.8.sp     ), val title1: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 18.sp,         lineHeight = 23.4.sp     ), val title2: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 16.sp,         lineHeight = 20.8.sp     ), val title3: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 14.sp,         lineHeight = 18.2.sp     ), val subtitle1: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W400,         fontSize = 18.sp,         lineHeight = 23.4.sp     ), val subtitle2: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W400,         fontSize = 16.sp,         lineHeight = 20.8.sp     ), val subtitle3: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W400,         fontSize = 14.sp,         lineHeight = 18.2.sp     ), val body1: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W400,         fontSize = 16.sp,         lineHeight = 20.8.sp     ), val body2: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W400,         fontSize = 14.sp,         lineHeight = 18.2.sp     ), val body3: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W400,         fontSize = 12.sp,         lineHeight = 15.6.sp     ), val caption: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 12.sp,         lineHeight = 15.6.sp     ), val overline1: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W400,         fontSize = 10.sp,         lineHeight = 13.sp     ), val overline2: TextStyle = TextStyle(         fontFamily = Inter,         fontWeight = FontWeight.W600,         fontSize = 10.sp,         lineHeight = 13.sp     )) |


## Functions


| Name | Summary |
|---|---|
| [AppTheme](-app-theme.html) | [androidJvm]<br>@Composable<br>fun [AppTheme](-app-theme.html)(colors: [AppColors](-app-colors/index.html) = AppTheme.colors, typography: [AppTypography](-app-typography/index.html) = AppTheme.typography, shapes: Shapes = MaterialTheme.shapes, content: @Composable() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [mainDarkColors](main-dark-colors.html) | [androidJvm]<br>fun [mainDarkColors](main-dark-colors.html)(primary: Color = Color(0xFF68A8FF), primaryVariant: Color = Color(0xFF222F41), background: Color = Color(0xFF0E0E0E), surface: Color = Color(0xFF232527), onPrimary: Color = Color(0xFF000000), onBackground: Color = Color(0xFFFFFFFF), onSurface: Color = Color(0xFFFFFFFF), onSurfaceVariant: Color = Color(0xFF68A8FF), error: Color = Color(0xFFFD7278), errorVariant: Color = Color(0xFFFFCED7), onError: Color = Color(0xFF000000), disabled: Color = Color(0xFF4E4E4E), onDisabled: Color = Color(0xFFFFFFFF), disabled2: Color = Color(0xFF1D1D1D), onDisabled2: Color = Color(0xFF737373), dataVisualization1: Color = Color(0xFFDB5AEE), dataVisualization1Variant: Color = Color(0xFFEFBDF7), dataVisualization2: Color = Color(0xFFFFB536), dataVisualization2Variant: Color = Color(0xFFFFDFAB), dataVisualization3: Color = Color(0xFF09C8FE), dataVisualization3Variant: Color = Color(0xFFACE8FE), dataVisualization4: Color = Color(0xFF1AD598), dataVisualization4Variant: Color = Color(0xFFB3EDD2), dataVisualization5: Color = Color(0xFF1AD598), dataVisualization5Variant: Color = Color(0xFFFFD1D3), success: Color = Color(0xFF74C76A), successVariant: Color = Color(0xFFCEDACA), warning: Color = Color(0xFFEECE55), warningVariant: Color = Color(0xFFF7E8B4), isLight: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false): [AppColors](-app-colors/index.html) |
| [mainLightColors](main-light-colors.html) | [androidJvm]<br>fun [mainLightColors](main-light-colors.html)(primary: Color = Color(0xFF4475E3), primaryVariant: Color = Color(0xFFDAE3F9), background: Color = Color(0xFFFBFBFB), surface: Color = Color(0xFFFFFFFF), onPrimary: Color = Color(0xFFFFFFFF), onBackground: Color = Color(0xFF000000), onSurface: Color = Color(0xFF000000), onSurfaceVariant: Color = Color(0xFF4475E3), error: Color = Color(0xFFFF3333), errorVariant: Color = Color(0xFFD14343), onError: Color = Color(0xFFFFFFFF), disabled: Color = Color(0xFFD7D7D7), onDisabled: Color = Color(0xFFFFFFFF), disabled2: Color = Color(0xFFF8F8F8), onDisabled2: Color = Color(0xFF9A9A9A), dataVisualization1: Color = Color(0xFF944ED7), dataVisualization1Variant: Color = Color(0xFF751EC7), dataVisualization2: Color = Color(0xFFF39C18), dataVisualization2Variant: Color = Color(0xFFC17A0D), dataVisualization3: Color = Color(0xFF00B0D7), dataVisualization3Variant: Color = Color(0xFF0D7491), dataVisualization4: Color = Color(0xFF1AD598), dataVisualization4Variant: Color = Color(0xFF00A670), dataVisualization5: Color = Color(0xFFFA5F4F), dataVisualization5Variant: Color = Color(0xFFCC4E40), success: Color = Color(0xFF2DC008), successVariant: Color = Color(0xFF00825D), warning: Color = Color(0xFFF5BF00), warningVariant: Color = Color(0xFFA36400), isLight: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true): [AppColors](-app-colors/index.html) |


## Properties


| Name | Summary |
|---|---|
| [Inter](-inter.html) | [androidJvm]<br>val [Inter](-inter.html): FontFamily |
| [OpenSans](-open-sans.html) | [androidJvm]<br>val [OpenSans](-open-sans.html): FontFamily |

