# C# SourceGenerator 학습

## 기초  
- [MS Docs](https://docs.microsoft.com/ko-kr/dotnet/csharp/roslyn-sdk/source-generators-overview )
- [(일어) Rider 에서 Source Generator 를 사용한 툴을 만드는 흐름 소개](https://qiita.com/Tanakancolle/items/b12c48e0cf0fe78af2ad )
- [(일어) VS2022을 사용한 Source Generator 입문](https://zenn.dev/mkmonaka/articles/8b9c1a87e35313 ) 
- [(일어) 소스 코드 생성하기](https://qiita.com/mad_khaki/items/2397f40823f748cba288 )
- [(일어) 코드 분서과 코드 생성](https://ufcpp.net/study/csharp/misc/analyzer-generator/ )
- [(일어) Unity에서 SourceGenerator를 동작 시키기까지](https://qiita.com/tsukuru_gamedev/items/ae4590dbe1db468c6aab )
- [(일어) Unity 용으로 Source Generator를 Rider에서 만드는 방법 보완](https://qiita.com/messhi/items/a0f4da92bfac55f5d11f )
- [(일어) Unity-AltSourceGenerator](https://github.com/sator-imaging/Unity-AltSourceGenerator )
- [Cysharp/UnitGenerator](https://github.com/Cysharp/UnitGenerator )
- [(일어) Source Generator를 좀 더 간단하게 사용하기](https://qiita.com/sator_imaging/items/d13d0969a9694c29b366 )
- [코드 생성을 위한 유틸리티 클래스](https://docs.google.com/document/d/e/2PACX-1vQwNqWJQsmRsXyXb7h5WCGbjyU-JExqZtBdhJ3vaTqgmgFqbOtBs4VZRt7NSjmG4fsOsifd2bcVhY04/pub )
- [(일어) IncrementalSourceGenerator 개발&디버그 방법](https://qiita.com/WiZLite/items/48f37278cf13be899e40 )
- [(일어) .NET 6에서 C# Incremental Source Generator 개발 방법](https://zenn.dev/pcysl5edgo/articles/6d9be0dd99c008 )
- [소스 생성기 만들기 - 1부 증분 생성기 만들기](https://forum.dotnetdev.kr/t/topic/2920 )
- [소스 생성기 만들기 2부 - 스냅샷 테스트로 증분 생성기 테스트](https://forum.dotnetdev.kr/t/topic/2988 )
- [소스 생성기 만들기 3부 - 통합 테스트 및 NuGet 패키징](https://forum.dotnetdev.kr/t/3-nuget/3010 )
- IncrementalGenerator를 적용한 Version 2 Source Generator 실습 [1](https://www.sysnet.pe.kr/2/0/12985 ) [2](https://www.sysnet.pe.kr/2/0/12986 )
- [(일어) C# 9.0에서 추가된 C# Source Generator와 이것으로 만들었던 ValueObjectGenerator 소개](https://qiita.com/RyotaMurohoshi/items/83775cf4ed1ce4f6378d  )
- [(일어) UnitGenerator - C# 9.0 SourceGenerator에 의한 ValueObject 패턴 자동 구현과  SourceGenerator 구현 Tips](http://neue.cc/2020/12/15_597.html )
- [(일어) C# 소스 제너레이터로 대상 프로젝트의 기존의 이름 공간을 얻는 방법](https://devadjust.exblog.jp/28519386/ )
- [(일어) IComparable을 자동 구현하는 ComparableGenerator을 공개하였다](https://zenn.dev/nuits_jp/articles/comparable-generator-release-1-2-0 )
- [(일어) Unity에서 "시리얼라이즈 하는 필드"와 "프로퍼티" 간결하게 쓰고 싶어서 SourceGenerator를 만들어 보았다](https://qiita.com/RyotaMurohoshi/items/05ba5a7e01b3e66f68ab )
- [(일어) C#9.0 SourceGenerator로 Readonly 구조체를 생성하는 Generator를 만들어 보았다](https://qiita.com/pierusan2010/items/d66b835240af30955da6 )
- [(일어) Tinyhand - C# 소스 생성기를 사용한 시리얼라이즈](https://qiita.com/archi-Doc/items/180904197a464e9b67fb )
- [(일어) C# Source Generator에서 GeneratedCodeAttribute의 버전 번호를 자동으로 주기](https://zenn.dev/k_maru/articles/auto_apply_verno_to_generated_code_attribute )
- [ufcpp/TextTemplateSourceGenerator](https://github.com/ufcpp/TextTemplateSourceGenerator )
- [New C# Source Generator Samples](https://devblogs.microsoft.com/dotnet/new-c-source-generator-samples/ )
- [csharp-source-generators](https://github.com/amis92/csharp-source-generators )   
- [(일어) IComparable를 자동 구현하는 ComparableGenerator를 공개하였다](https://zenn.dev/nuits_jp/articles/2021-02-16-comparable-generator-release-1-2-0 ) 
- [(일어) 2022년 C#(Incremental) Source Generator 개발 방법](https://neue.cc/2022/12/16_IncrementalSourceGenerator.html )
- [(일어) StructureOfArraysGenerator - C#으로 SoA를 간단하게 이용하기 위한 Source Generator](https://neue.cc/2023/01/27_StructureOfArraysGenerator.html )
- [(일어) SimdLinq - LINQ를 그대로 SIMD 대응하여 초고속화한 라이브러리](https://neue.cc/2023/01/30-SimdLinq.html )
- [(일어) Source Generator 에서 스크립트 이외의 파일에 접근하기](https://zenn.dev/ruccho/articles/e201fcf1a11b8d ) 
- [(일어) Source Generator 로 프로퍼티를 자동 구현하기](https://qiita.com/amenone_games/items/25c857608af0138eb646 )


## IDE 
- [(일어) Rider】SourceGeneratorをデバッグする方法  https://qiita.com/amenone_games/items/0a99f38fd08911b62c3a

  
## 응용
- [(일어) Incremantal SourceGenerator プロジェクトの作り方  https://qiita.com/amenone_games/items/762cbea245f95b212cfa
- [(일어) DecoratorパターンをSource Generatorで作成したら便利だった  https://qiita.com/kwhrkzk/items/f0ef8959632348d98005
- [(일어) Source GeneratorでC#のソースコードからPlantUMLのクラス図を生成する  https://qiita.com/pierusan2010/items/cdd628f202a9767cf65d
  
## Unity  
- [(일어) dotnetコマンドでUnity用SourceGeneratorを自作する  https://qiita.com/ma_comu/items/f5b055badcc4dd047ce8
