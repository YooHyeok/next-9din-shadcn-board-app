# Next.js 프로젝트 세팅
<details>
<summary>펼치기/접기</summary>
<br>

1. 설치 명령 입력
   ```
   PS C:\프로젝트설치 상위경로> npx create-next-app@latest {프로젝트명} --typescript --tailwind --eslint
   ```

2. 패키지 설치 확인
   ```
   Need to install the following packages:
     create-next-app@15.3.3
   Ok to proceed? (y) y
   ```

3. src 디렉토리 생성 여부 - `Yes 선택`
   ```
   ? Would you like your code inside a `src/` directory? » No / Yes  
   ```

4. App Router 사용 여부 - `Yes 선택`
   ```
   ? Would you like to use App Router? (recommended) » No / Yes
   ```

5. Turbopack 번들러 사용 여부 - `Yes 선택`
   ```
   ? Would you like to use Turbopack for `next dev`? » No / Yes
   ```

6. import alias 사용 여부 - `Yes 선택`
   ```
   ? Would you like to customize the import alias (`@/*` by default)? » No / Yes
   ```

7. import alias 설정 - `Enter로 기본값 사용`
   ```
   ? What import alias would you like configured? » @/*
   ```

9. 서버 실행
   ```
   cd {프로젝트명}
   npm run dev
   ```

</details>
<br>

# shadcn/ui 설치 및 초기화
<details>
<summary>펼치기/접기</summary>
<br>

1. 설치 명령 입력
   ```
   PS C:\프로젝트 경로> npx shadcn@latest init
   ```

2. 패키지 설치 확인
   ```
   Need to install the following packages:
     shadcn@2.6.3
   Ok to proceed? (y) y
   ```

3. 기본 색상 선택 - `Slate 선택`
   ```
   ? Which color would you like to use as the base color? » - Use arrow-keys. Return to submit.
       Neutral
       Gray
       Zinc
       Stone
   >   Slate
   ```

4. CSS 변수 사용 여부 - `Yes 선택`
   ```
   ? Would you like to use CSS variables for theming? » No / Yes
   ```

5. 설치 완료 후 컴포넌트 추가 예시
   ```
   npx shadcn@latest add button
   npx shadcn@latest add input
   npx shadcn@latest add card
   ```

</details>
<br>