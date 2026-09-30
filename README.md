# C++ 基礎

## 目的
Unreal Engine を学ぶ前に、ゲームプログラミングに必要なC++の基礎能力を身につける。
「C++の文法を覚える」のではなく、C++を使って自分で設計・実装できることを目的とする。

## 扱うトピック

### 言語基礎
- class / struct
- constructor / destructor
- reference
- pointer
- const
- enum
- namespace
- header / source

### オブジェクト設計
- encapsulation
- inheritance
- virtual
- polymorphism
- interface 的な設計
- composition

### リソース管理
- RAII
- ownership
- lifetime
- copy
- move
- `std::unique_ptr`
- `std::shared_ptr`

### STL
- `std::vector`
- `std::array`
- `std::string`
- `std::unordered_map`
- `std::optional`
- `std::variant`
- iterator
- algorithm

### 関数
- lambda
- function object
- `std::function`

### ビルド
- CMake
- Debug / Release
- compiler warnings
- debugger

### エラー処理
- return value
- exception
- `std::optional`
- `std::expected`

## 実践課題
ゲームそのものではなく、ゲームで使う小さなモデルを作る。
例えば、
- Character
- Weapon
- Inventory
- Item
- Enemy
- Health
- Damage
- GameState

などの基本的なモデルを作る。

## やらないこと
- ゲーム自体を作る
- 高度なモデルを作る

## 完了条件
以下を満たすこと：

- [ ] C++で小規模なプログラムを自力で設計・実装できる
- [ ] class / struct の責務を自分で決められる
- [ ] ownership / lifetime を説明できる
- [ ] pointer / reference の使い分けを説明できる
- [ ] inheritance と composition の使い分けを説明できる
- [ ] STL を使ってデータ構造を実装できる
- [ ] debugger で自分のコードを追跡できる
- [ ] CMake でプロジェクトを構築できる
