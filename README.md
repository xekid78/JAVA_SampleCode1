# JavaRandomDice
サイコロの目をランダムに出力

## 処理
randomメソッドを使用して1 ～ 6のランダムな数字を使って、「サイコロの目は**です」  と出力します。

## コード
```
public class sample1 {　　
	public static void main(String[] args) {　　
		double rand = Math.random() * 6 + 1;　　
		int num = (int)rand;　　
		System.out.println("サイコロの目は" + num + "です");　　
		
	}　　
　　
}　　
　　
```

## 開発環境
| 開発ツール |  |
|:-|:-|
| 統合開発環境(IDE) | Eclipse 4.7.0 Oxygen |
| 開発言語 | Java8 |
