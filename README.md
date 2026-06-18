# Expired Domain Notice Template

![License](https://img.shields.io/badge/license-CC--BY--SA%204.0-blue)

A reusable HTML template for publishing security notices about expired domains acquired by third parties.

## 概要

期限切れとなったドメインを第三者が取得した際、過去の利用者や関係者に対して情報セキュリティ上の注意喚起を行うためのHTMLテンプレートです。

ドメインの失効後には、第三者による再登録（いわゆるドロップキャッチを含みます。）が行われることがあり、メールの誤送信、なりすまし、外部サービス連携の残存、アカウントの不正利用、過去のリンクからの誤アクセスなど、さまざまなリスクが生じる可能性があります。本テンプレートは、こうしたリスクについて周知するとともに、過去の登録者・管理者・運営者や利用者に対して確認・対応を促すことを目的として作成されています。

テンプレートには、以下の内容が含まれています。

- ドメインの現状に関する注意喚起
- 過去の登録者・管理者・運営者向けの推奨対応
- 利用者向けの注意事項
- 国内外の実際の事例紹介
- ドメインのライフサイクル管理に関する参考情報
- 運営者の立場や免責事項に関する記載
- メール非受信運用（Null MX、SPF、DMARC）に関する説明例
- 問い合わせ案内の例

本テンプレートは、日本国内で日本語により運営されていたウェブサイトを主な想定対象として作成していますが、必要に応じて内容を編集し、他の言語や地域の事情に合わせて利用できます。

### 免責事項

本プロジェクトは、期限切れとなったドメインが第三者に取得された場合に生じ得る情報セキュリティ上のリスクについて可視化・周知することを目的としたセキュリティ研究の一環です。

本テンプレートは、適法に取得されたドメインについて、公開情報に基づき、法令および第三者の権利を尊重した形で利用されることを前提として提供しています。

本テンプレートは、フィッシング、なりすまし、不正アクセス、嫌がらせその他の違法または悪意ある行為を助長・推奨するものではありません。

## ライセンス

本テンプレートは、同様の状況に直面した方が再利用・改変しやすいよう、[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.ja)ライセンスの下で公開しています。利用、共有、改変および再配布が認められていますが、出典表示（Attribution）および改変物の同一ライセンスでの公開（ShareAlike）の条件に従ってください。

## 関連プロジェクト

### unused-domain-check

本テンプレートを設置・運用する場合は、**unused-domain-check** も併せて利用できます。

unused-domain-check は、Null MX、SPF、DMARC などのDNSレコードを確認し、利用を終了したドメインや未使用ドメインについて、メールに起因するリスクを低減するための設定が適切に行われているかを確認するPOSIXシェルスクリプトです。

リポジトリ:
https://github.com/rsato/unused-domain-check

----

## Overview

This repository provides an HTML template intended for publishing security notices related to expired domains that have been acquired by third parties.

When a domain expires and becomes available for re-registration, it may be acquired by a third party, including through drop catching. Residual trust relationships and configurations associated with that domain may create security risks for former operators, users, and related parties.
This template is designed to help notify affected parties of such risks and encourage appropriate mitigation and remediation actions.

### Contents

- Notice regarding the current status of the domain
- Recommended actions for former registrants, administrators, and operators
- Guidance for users and related parties
- Examples of real-world incidents involving expired domains
- References on domain lifecycle management
- Disclaimers and statements regarding the current operator's position
- Example wording for non-receiving email configurations (Null MX, SPF, and DMARC)
- Contact information examples

This template was originally written for websites previously operated in Japanese, but it may be adapted for other languages and jurisdictions as appropriate.

If you use or adapt this template, issue reports, improvements, translations, and examples of real-world usage are welcome.

### Disclaimer

This project is part of security research intended to raise awareness about the risks associated with expired domains acquired by third parties.

This template is provided for legitimate security awareness purposes only. It is intended to be used only where the domain has been lawfully acquired and the published information is accurate, appropriately sourced, and compliant with applicable laws and the rights of third parties.

The author does not endorse or encourage phishing, impersonation, unauthorized access, harassment, or any other malicious or unlawful use of expired domains.

This repository does not provide support for individual expired domains or former websites and services.

## Contributing

Bug reports, suggestions, translations, and improvements are welcome. Please feel free to open an Issue or Pull Request.

## License

This work is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). You are free to share and adapt the material for any purpose, provided that you give appropriate attribution and distribute derivative works under the same license.

## Related project

### unused-domain-check

If you use this template, you may also find **unused-domain-check** useful.

It is a POSIX shell script that verifies whether an unused or retired domain has been configured to reduce email-related risks by checking DNS records such as Null MX, SPF, and DMARC.

Repository: https://github.com/rsato/unused-domain-check
