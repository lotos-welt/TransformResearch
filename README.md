# TransformResearch

Unity上で使用できるオブジェクト・コンポーネントを検索するクラスです。

＜使い方の例＞

「指定したコンポーネントの子オブジェクトを取得する」場合はこのように呼び出します。
var components = TransformResearch.SelfGetComponentArray<BoxCollider>(gameObject, true);

指定したゲームオブジェクトの子オブジェクトに付いている指定したコンポーネントを返します。

