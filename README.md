# NAVER Map Android SDK Demo

## How To Run

- 네이버 지도 SDK를 사용하기 위해서는 네이버 클라우드 플랫폼에서 클라이언트 ID를 발급받고, 발급받은 ID를 SDK에 지정해야 합니다.
- 클라이언트 ID 발급
  1. [네이버 클라우드 플랫폼](https://www.ncloud.com) 콘솔의 **AI·Application Service > AI·NAVER API > Application**에서 애플리케이션을 등록합니다.
  2. **AI·Application Service > AI·NAVER API > Application**에서 등록한 애플리케이션을 선택해 Client ID값을 확인합니다.
  3. **AI·Application Service > AI·NAVER API > Application**의 **변경** 화면에서 **Maps**가 선택되어 있는지 확인합니다.
- 클라이언트 ID 지정
  - [`client_id.xml`](app/src/main/res/values/client_id.xml)의 `naver_map_sdk_client_id`에 네이버 클라우드 플랫폼에서 발급받은 클라이언트 ID를 입력합니다.
- 자세한 내용은 [시작하기](https://navermaps.github.io/android-map-sdk/guide/1.html)를 참고하십시오.

## Reference

- [개발 가이드](https://navermaps.github.io/android-map-sdk/)
- [API 레퍼런스](https://navermaps.github.io/android-map-sdk/reference/)
- [Changelog](https://github.com/navermaps/android-map-sdk/blob/master/CHANGELOG.md)

## License

Copyright (c) 2018-2019 NAVER Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
