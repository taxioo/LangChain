# LangChain

## 환경 설정

### API 키 설정

이 프로젝트는 Anthropic Claude API를 사용합니다. API 키를 설정해야 합니다.

#### 방법 1: .env 파일 사용 (권장)

프로젝트 루트 디렉토리에 `.env` 파일을 생성하고 다음 내용을 추가하세요:

```
ANTHROPIC_API_KEY=your_api_key_here
```

API 키는 [Anthropic Console](https://console.anthropic.com/)에서 발급받을 수 있습니다.

#### 방법 2: 환경 변수로 설정

터미널에서 다음 명령어를 실행하세요:

```bash
export ANTHROPIC_API_KEY=your_api_key_here
```

#### 방법 3: 코드에서 직접 설정 (개발/테스트용)

코드에서 직접 설정할 수도 있지만, 보안상 권장하지 않습니다:

```python
import os
os.environ['ANTHROPIC_API_KEY'] = 'your_api_key_here'
```

## 설치

```bash
pip install -r requirements.txt
```

## 사용법

Jupyter Notebook을 실행하여 예제를 확인하세요:

```bash
jupyter lab
```
