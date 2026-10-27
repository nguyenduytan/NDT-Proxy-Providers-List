<div align="center">

<h1>🌐 NDT Proxy Providers List</h1>
<p><strong>Chọn đúng proxy. Hiểu đúng giá. Đo bằng kết quả thực tế.</strong></p>
<p>Residential · ISP · Datacenter · Mobile · Scraping infrastructure</p>

<a href="#pricing"><img alt="Pricing reviewed" src="https://img.shields.io/badge/Price_review-2026--10--27-2563eb?style=flat-square"></a>
<a href="#methodology"><img alt="No affiliate links" src="https://img.shields.io/badge/Affiliate_links-None-16a34a?style=flat-square"></a>
<a href="LICENSE"><img alt="MIT license" src="https://img.shields.io/badge/License-MIT-64748b?style=flat-square"></a>
<a href="CONTRIBUTING.md"><img alt="Contributions welcome" src="https://img.shields.io/badge/Contributions-Welcome-0d9488?style=flat-square"></a>
<a href="https://github.com/nguyenduytan/NDT-Proxy-Providers-List/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/nguyenduytan/NDT-Proxy-Providers-List?style=flat-square"></a>

<p><a href="#quick-start">Chọn nhanh</a> · <a href="#pricing">Bảng giá</a> · <a href="#directory">Danh bạ</a> · <a href="#cost">Tính chi phí</a> · <a href="#benchmark">Đánh giá</a></p>
</div>

---

Danh sách độc lập dành cho người cần chọn proxy cho kiểm thử địa lý, nghiên cứu và thu thập dữ liệu được phép. Giá được tách theo **GB, IP và thời gian thuê**; không đánh đồng giá quảng cáo ở gói lớn với số tiền phải trả khi bắt đầu.

> [!NOTE]
> **Snapshot nghiên cứu: 27/10/2026.** Đây là đối chiếu tài liệu công khai, chưa phải benchmark tốc độ hoặc tỷ lệ thành công. Các mục danh bạ mở rộng chưa được xác minh toàn bộ giá/tính năng. Link nguồn ở ngay từng dòng; xem [SOURCES.md](SOURCES.md) để biết phạm vi kiểm tra.

<a id="quick-start"></a>
## 🧭 Chọn nhanh theo nhu cầu

| Nhu cầu | Shortlist để thử | Lý do và điều cần kiểm tra |
|---|---|---|
| Residential ngân sách nhỏ | [SocksNode](https://socksnode.com/), [Evomi](https://evomi.com/), [DataImpulse](https://dataimpulse.com/) | So chi phí nạp ban đầu, thời hạn traffic và pool tại quốc gia cần dùng |
| Traffic đều khoảng 100 GB/tháng | [Evomi](https://evomi.com/pricing), [SocksNode](https://socksnode.com/en/pricing) | So subscription với prepaid; xem ví dụ chi phí bên dưới |
| IP cố định cho phiên dài | [IPRoyal](https://iproyal.com/), [ProxyEmpire](https://proxyempire.io/), [Oxylabs](https://oxylabs.io/) | Kiểm tra dedicated/shared, chính sách đổi IP và băng thông |
| Datacenter giá thấp | [Webshare](https://www.webshare.io/), [Evomi](https://evomi.com/), [SocksNode](https://socksnode.com/) | Chỉ phù hợp nếu website chấp nhận IP datacenter; giá theo IP không phải theo GB |
| Carrier/mobile | [SocksNode](https://socksnode.com/), [DataImpulse](https://dataimpulse.com/), [Evomi](https://evomi.com/) | So gói thuê port với per-GB; kiểm tra geo/carrier và phụ phí targeting |
| Nhiều sản phẩm, quản trị đội nhóm | [Bright Data](https://brightdata.com/), [Oxylabs](https://oxylabs.io/), [SOAX](https://soax.com/) | Đánh giá tài liệu, phân quyền, hợp đồng và hỗ trợ; không mặc định chất lượng tốt nhất |

**Ghi nhận từ NDT:** Evomi và SocksNode có giá dễ tiếp cận và trải nghiệm sử dụng cá nhân khá ổn. Đây là nhận xét của người duy trì, không phải phép đo độc lập hay cam kết phù hợp mọi website.

<a id="types"></a>
## 🧱 Hiểu đúng từng loại

| Loại | Đặc trưng | Cách tính phí thường gặp | Khi nào nên thử |
|---|---|---|---|
| 🏢 Datacenter | IP từ hạ tầng hosting | IP/tháng hoặc GB | Tốc độ và chi phí quan trọng, website cho phép |
| 🏠 Rotating residential | Pool IP dân cư; có thể xoay hoặc giữ phiên | GB; đôi khi theo request/IP | Kiểm thử nội dung theo địa lý, lấy mẫu nhiều vùng |
| 📌 ISP / static residential | IP đăng ký với ISP, thường được phục vụ trên hạ tầng máy chủ | IP/tháng; có gói tính GB | Cần địa chỉ ổn định; không đồng nghĩa thiết bị dân cư thật |
| 📱 Mobile | IP mạng di động, có thể dùng chung qua CGNAT | GB, port/giờ/ngày/tháng | Kiểm thử qua carrier; cần xác minh loại thuê và chia sẻ |
| 🔄 Sticky | Cố giữ cùng IP trong khoảng thời gian | Tùy sản phẩm | Phiên nhiều bước; không phải bảo đảm IP tồn tại mãi |
| 🧩 Scraper API | Nhà cung cấp vận hành proxy/render/retry | Request, credit, kết quả hoặc GB | Muốn mua đầu ra thay vì vận hành proxy |

HTTP(S), SOCKS5 và UDP là khả năng giao thức, không phải loại nguồn IP. IPv6 thường rẻ hơn IPv4 nhưng website đích phải hỗ trợ. “Unlimited” có thể vẫn giới hạn tốc độ, concurrency hoặc fair use.

<a id="pricing"></a>
## 💵 Bảng giá có điều kiện

**Quy ước:** `$` = USD. **Từ** = mức thấp được công bố, có thể cần mua số lượng lớn. **Chưa chốt** = chưa đủ dữ liệu để đưa ra giá so sánh. Thuế/phí thanh toán chưa được cộng trừ khi ghi rõ. Bảng không phải báo giá hoặc xếp hạng chất lượng.

### 🏠 Residential theo GB

| Provider / nguồn chính thức | Giá đọc được | Điều kiện | Nhận định mua hàng |
|---|---|---|---|
| [Evomi](https://evomi.com/pricing) | $49/tháng cho 100 GB; PAYG $0.99/GB từ 15 GB | PAYG không hết hạn; gói tháng khác cơ chế | Giá thấp nếu dùng đều; không dùng $0.49 để tính đơn hàng 5 GB |
| [SocksNode](https://socksnode.com/en/pricing) | 5 GB $4.50; 10 GB $8.50; 100 GB $73 | Prepaid không hết hạn; headline từ $0.53/GB không phải gói 5 GB | Dễ thử nhỏ, hợp traffic không đều |
| [DataImpulse](https://dataimpulse.com/) | $1/GB | Trang công bố PAYG, không hết hạn; mức nạp cần xác nhận khi mua | Đơn giá dễ hiểu; cần kiểm tra hạn chế website/giao thức |
| [PacketStream](https://packetstream.io/terms-of-service) | $1/GB | Mua tối thiểu $50 theo điều khoản công khai | Đơn giá thấp nhưng ngân sách thử ban đầu không phải $1 |
| [Decodo](https://decodo.com/proxies/residential-proxies) | Từ $2/GB | Chưa chốt dung lượng/term của mức thấp nhất trong lượt đọc này | Yêu cầu báo giá đúng số GB; có residential, ISP, mobile và DC |
| [IPRoyal](https://iproyal.com/residential-proxies/) | Trang sản phẩm nêu gói tùy chỉnh từ $1.75/GB | Không coi là giá mua lẻ | Kiểm tra gói, traffic expiry và chi phí targeting |
| [ProxyEmpire](https://proxyempire.io/pricing/) | PAYG 1 GB $3.50; từ $1.50/GB ở mức quảng cáo | Trang đang áp dụng khuyến mại 50%; có rollover | Không coi mức giảm là giá thường xuyên |
| [SOAX](https://soax.com/pricing) | Sandbox $5/$4/$2 mỗi GB theo geo tier; Builder $200/tháng | Builder có 200 credit, rate $3/$2.25/$1.20; cộng top-up nếu vượt | Tính theo quốc gia IP đầu ra; fee đã gồm credit, tránh cộng hai lần |
| [Oxylabs](https://oxylabs.io/pricing) | Starter $30/tháng; residential $6/GB, tối đa 5 GB nếu dùng riêng | Gói dùng chung nhiều sản phẩm; Flexible $500 có rate $4/GB | Không thể vừa tiêu cùng credit cho residential vừa tính đủ cho mobile |
| [Rayobyte](https://rayobyte.com/) | Premium từ $0.50/GB; Scale quảng cáo từ $0.0095/GB | Chưa chốt volume tối thiểu và pool của mức Scale | Hai sản phẩm khác nhau; không suy ra chất lượng tương đương |
| [Bright Data](https://brightdata.com/pricing) | Chưa chốt giá động | Theo sản phẩm, cam kết và cấu hình | So giá mạng proxy trực tiếp với API managed riêng |
| [Geonode](https://geonode.com/) | Proxy quảng cáo từ $0.27/GB | Trang còn bán API theo concurrency; chưa chốt tier proxy | Không dùng giá API thay cho giá mạng proxy |
| [Thordata](https://www.thordata.com/) | Residential quảng cáo $0.65/GB | Chưa xác minh gói tối thiểu tương ứng | Chỉ là mốc để hỏi báo giá, không phải giá thử nhỏ |

### 🏢 Datacenter theo GB

| Provider / nguồn | Mua nhỏ hoặc PAYG | Mức volume | Điều kiện cần chú ý |
|---|---|---|---|
| [Evomi](https://evomi.com/pricing) | $0.45/GB | $0.30/GB trên gói 1,000 GB | Kiểm tra minimum PAYG trước nạp |
| [SocksNode](https://socksnode.com/en/pricing) | 1 GB $0.66; 10 GB $5.70 | 100 GB $49; 10 TB $2,969.60 | Trang dùng 1 TB = 1,024 GB; không hết hạn |
| [DataImpulse](https://dataimpulse.com/) | Công bố $0.50/GB | Hỏi mức volume | Tách khỏi pool residential |
| [Oxylabs](https://oxylabs.io/pricing) | Starter $0.60/GB | Flexible $0.45/GB; enterprise từ $0.40 | Rate phụ thuộc subscription/credit |
| [Rayobyte](https://rayobyte.com/) | Chưa chốt mức mua nhỏ | Quảng cáo từ $0.008/GB | Không đưa vào phép tính đơn hàng nhỏ khi chưa biết minimum |

### 📌 ISP và datacenter theo IP

| Provider / nguồn | Sản phẩm / giá công bố | Cần phân biệt |
|---|---|---|
| [Webshare](https://www.webshare.io/pricing) | Proxy Server: 100 IP $2.99/tháng; có 10 IP miễn phí | Không mặc định 100 dedicated IP hoặc unlimited bandwidth; xem đúng cấu hình |
| [Evomi](https://evomi.com/pricing) | Static residential shared từ $1/IP, subscription | Chưa coi $1/IP là dedicated; kiểm tra kỳ hạn và minimum |
| [SocksNode](https://socksnode.com/en/pricing) | Menu nêu ISP từ $2.32/tháng; DC từ $0.72/tháng | Giá ISP trên homepage khác; ưu tiên cấu hình country/term tại checkout |
| [IPRoyal](https://iproyal.com/pricing/) | ISP từ $1.80/proxy; DC từ $1.39/proxy | Chưa chốt kỳ thuê/minimum tương ứng; không tự quy thành IP/tháng |
| [ProxyEmpire](https://proxyempire.io/pricing/) | ISP từ $2/IP | Xác nhận có cộng traffic hoặc phí duy trì không |
| [Rayobyte](https://rayobyte.com/) | Static ISP từ $0.95/IP/tháng; DC từ $0.85/IP/tháng | Phân biệt semi-dedicated, dedicated và số IP tối thiểu |
| [Oxylabs](https://oxylabs.io/pricing) | Starter: ISP $1.50/IP; dedicated ISP $3/IP; dedicated DC $2/IP | Dùng chung subscription; giới hạn sản phẩm và thời hạn theo plan |
| [Proxy-Cheap](https://www.proxy-cheap.com/) | Cấu hình ISP Basic đang hiển thị từ $2.71/tháng | Shared tối đa 3 người và chỉ 1 GB đi kèm ở cấu hình đọc được |
| [Proxy-Seller](https://proxy-seller.com/) | IPv4 từ $0.49; ISP từ $0.98; IPv6 từ $0.02 | Headline chưa đủ kỳ hạn/địa lý: không dùng để xếp hạng IP/tháng |

### 📱 Mobile theo traffic hoặc port

| Provider / nguồn | Giá đọc được | Điều kiện quan trọng |
|---|---|---|
| [Evomi](https://evomi.com/pricing) | PAYG $3.98/GB; volume từ $2.20/GB | Giá thấp nhất dành gói lớn; minimum PAYG cần xác nhận |
| [SocksNode](https://socksnode.com/en/pricing) | 5 GB $19.50; 100 GB $260; 2 TB $4,710.40 | Targeting state/city/ASN tính traffic 2×; country theo rate gốc |
| [SocksNode](https://socksnode.com/en/pricing) | Economy US $30/30 ngày; Basic $40/30 ngày | 15 GB/ngày đi kèm; thuê port không đồng nghĩa unlimited |
| [DataImpulse](https://dataimpulse.com/) | $2/GB | Kiểm tra minimum, carrier và country trước mua |
| [ProxyEmpire](https://proxyempire.io/pricing/) | Rotating từ $2/GB; dedicated từ $20/ngày | Sản phẩm và giá volume/khuyến mại khác nhau |
| [Oxylabs](https://oxylabs.io/pricing) | Starter $7.50/GB; Flexible $5/GB | Rate theo gói chung, không phải gói riêng không cam kết |
| [SOAX](https://soax.com/pricing) | Cùng hệ rate residential/mobile theo geo tier | Country đầu ra quyết định tier, không phải vị trí người mua |

<a id="directory"></a>
## 🗂️ Danh bạ mở rộng

Bảng giá ở trên có 16 provider chính. Danh bạ sau bổ sung các lựa chọn để nghiên cứu, giúp bao phủ cả những tên trong nguồn tham khảo lẫn provider khác. **Việc có mặt không phải chứng nhận chất lượng.** Những dòng này chưa chốt giá hiện hành; cần kiểm tra sản phẩm, pháp nhân, nguồn IP và điều khoản trực tiếp trước mua. Không lấy giá cũ ở nguồn tham khảo làm giá mới.

| Provider | Website trực tiếp | Trạng thái biên tập |
|---|---|---|
| ASocks | [asocks.com](https://asocks.com/) | Cần đối chiếu lại giá / pool |
| AstroProxy | [astroproxy.com](https://astroproxy.com/) | Cần đối chiếu lại phí port và GB |
| BestProxy | [bestproxy.com](https://bestproxy.com/) | Cần chốt expiry và minimum |
| CyberYozh | [cyberyozh.com](https://cyberyozh.com/) | Cần chốt đúng loại proxy |
| Floppydata | [floppydata.com](https://floppydata.com/) | Đã xem trang sản phẩm; chưa chốt cấu hình giá |
| FlyProxy | [flyproxy.com](https://www.flyproxy.com/) | Cần đối chiếu lại plan |
| GonzoProxy | [gonzoproxy.com](https://gonzoproxy.com/) | Cần kiểm tra điều kiện unlimited |
| HypeProxy | [hypeproxy.io](https://hypeproxy.io/) | Cần kiểm tra inventory / kỳ thuê |
| IPCook | [ipcook.com](https://www.ipcook.com/) | Cần đối chiếu expiry và IP/GB |
| IPFoxy | [ipfoxy.com](https://www.ipfoxy.com/) | Cần chốt plan và locale |
| IPLoop | [iploop.io](https://iploop.io/) | Cần đối chiếu API / giá |
| IpnProxy | [ipnproxy.com](https://ipnproxy.com/) | Cần chốt ngày thuê và traffic |
| MangoProxy | [mangoproxy.com](https://mangoproxy.com/) | Cần đối chiếu lại tier |
| NodeMaven | [nodemaven.com](https://nodemaven.com/) | Đã xem sản phẩm residential/mobile/ISP; chưa chốt giá |
| NstProxy | [nstproxy.com](https://www.nstproxy.com/) | Cần chốt IPv4/IPv6 và plan |
| OkeyProxy | [okeyproxy.com](https://www.okeyproxy.com/) | Cần đối chiếu lại minimum |
| PapaProxy | [papaproxy.net](https://papaproxy.net/) | Cần chốt country / loại IP |
| Proxy.market | [proxy.market](https://proxy.market/) | Cần chốt country / kỳ thuê |
| Proxy-store | [proxy-store.com](https://proxy-store.com/) | Cần phân biệt shared/private |
| Proxymus | [proxymus.net](https://proxymus.net/) | Cần đối chiếu lại giá |
| ProxyScrape | [proxyscrape.com](https://proxyscrape.com/) | Đã xem sản phẩm; cần chốt premium/dedicated/unlimited |
| ProxyShard | [proxyshard.com](https://proxyshard.com/) | Cần đối chiếu lại plan |
| ProxyWing | [proxywing.com](https://proxywing.com/) | Cần chốt ISP/DC/residential |
| RapidProxy | [rapidproxy.io](https://www.rapidproxy.io/) | Cần đối chiếu lại plan |
| SX | [sx.org](https://sx.org/) | Cần kiểm tra đơn vị IP/GB |
| IPRocket | [iprocket.io](https://iprocket.io/) | Bổ sung để nghiên cứu; chưa xác minh giá |
| Infatica | [infatica.io](https://infatica.io/) | Bổ sung để nghiên cứu; chưa xác minh giá |
| Nimble | [nimbleway.com](https://www.nimbleway.com/) | Tách mạng proxy khỏi API dữ liệu |
| Rayo / Blazing SEO | [rayobyte.com](https://rayobyte.com/) | Alias lịch sử; không đếm thêm provider |
| Smartproxy | [decodo.com](https://decodo.com/) | Alias lịch sử; không đếm thêm provider |
| IPRoyal / PacketStream / Evomi | Xem bảng giá phía trên | Không đếm trùng theo từng loại proxy |

<details>
<summary><strong>📦 Tên cũ / mục cần kiểm tra thêm trước khi đưa vào shortlist</strong></summary>

| Tên trong các danh sách cũ | Link trực tiếp | Vì sao chưa xếp hạng |
|---|---|---|
| LunaProxy | [lunaproxy.com](https://www.lunaproxy.com/) | Chưa xác minh nguồn IP và trạng thái thương mại hiện tại |
| 922Proxy | [922proxy.com](https://www.922proxy.com/) | Chưa xác minh nguồn IP và trạng thái thương mại hiện tại |
| ABCProxy | [abcproxy.com](https://www.abcproxy.com/) | Chưa xác minh nguồn IP và trạng thái thương mại hiện tại |
| IP2World | [ip2world.com](https://ip2world.com/) | Trang có thông báo quay lại; cần thẩm định nguồn IP và dịch vụ hiện tại |
| NetNut | [netnut.io](https://netnut.io/) | Chưa xác minh trạng thái hiện tại; không tái sử dụng giá lịch sử |
| IPIDEA | [ipidea.net](https://www.ipidea.net/) | Không đọc được nguồn chính thức trong đợt rà soát |

Không suy ra dịch vụ đã ngừng hoạt động hoặc có hành vi sai chỉ từ lỗi truy cập. Các tên này được giữ để tra cứu, không phải khuyến nghị mua.

</details>

<a id="cost"></a>
## 🧮 Phân tích chi phí thực

### Ví dụ 100 GB residential

| Phương án | Tiền cần chi theo dữ liệu đã đọc | Ý nghĩa |
|---|---:|---|
| Evomi monthly | $49/tháng | Hiệu quả nếu dùng gần hết quota trong chu kỳ |
| Evomi PAYG | $99 cho 100 GB ở rate $0.99 | Không cam kết tháng; traffic mua lẻ không hết hạn |
| SocksNode prepaid | $73 cho 100 GB | Không hết hạn; có thể chia dùng nhiều tháng |
| PacketStream | $100 cho 100 GB | Đáp ứng minimum $50 |
| SOAX Builder, Tier 1 | $300 cho 100 GB | $200 gồm credit + $100 top-up theo calculator của hãng |

Nguồn cho phép tính: [Evomi](https://evomi.com/pricing), [SocksNode](https://socksnode.com/en/pricing), [PacketStream](https://packetstream.io/terms-of-service), [SOAX](https://soax.com/pricing). Không cộng thuế, phí nạp hoặc chiết khấu riêng. Đây là so sánh hóa đơn, chưa đánh giá tỷ lệ thành công.

Nếu chỉ dùng 10 GB của gói Evomi $49 trong một tháng, chi phí trên lượng thực dùng là **$4.90/GB**; không phải $0.49. Ngược lại, prepaid 100 GB chưa dùng hết vẫn là số dư, không nên tính toàn bộ vào chi phí một tháng nếu còn dùng tiếp.

### Đo bằng dữ liệu dùng được

```text
chi phí / 1.000 kết quả hợp lệ
= (phí proxy + phí API/solver + compute + phí bắt buộc) / số kết quả hợp lệ × 1.000

giá hiệu dụng / GB thực dùng = tổng tiền chi trong phạm vi so sánh / GB đã dùng
```

Ví dụ giả định: A tốn $20 và có 80,000 kết quả hợp lệ → $0.25/1K. B tốn $15 nhưng chỉ có 40,000 → $0.375/1K. A đắt hơn trên hóa đơn nhưng rẻ hơn trên kết quả. Đây là ví dụ toán học, không phải benchmark provider.

### Những khoản dễ bỏ sót

- **Retry và traffic hai chiều:** request lỗi vẫn có thể bị tính băng thông.
- **Targeting:** geo/ASN/carrier có thể tăng rate hoặc số GB bị trừ.
- **Session:** sticky có thể bị mất khi node rời mạng; fixed IP cần chính sách thay thế rõ ràng.
- **Concurrency:** nhiều credential không có nghĩa nhiều exit IP độc lập.
- **“Unlimited”:** cần đọc fair use, giới hạn tốc độ và traffic mỗi ngày.
- **Thời hạn và hoàn tiền:** phân biệt expiry của GB, số dư tài khoản và kỳ thuê IP.
- **API managed:** một kết quả có thể dùng nhiều credit; render và premium target có thể có hệ số.

<a id="managed"></a>
## 🧩 Hạ tầng managed nên so riêng

| Nhà cung cấp | Hướng sản phẩm cần đánh giá | Mẫu chi phí |
|---|---|---|
| [Bright Data](https://brightdata.com/pricing) | Browser API, SERP API, Unlocker, dataset | Request/result/traffic tùy sản phẩm |
| [Oxylabs](https://oxylabs.io/pricing) | Search, Scrape, Agent Browser | Subscription + credit |
| [Decodo](https://decodo.com/) | Web Data API, proxy, browser-related workflows | Tùy endpoint và độ phức tạp |
| [Geonode](https://geonode.com/) | Scraping API và proxy | API theo concurrency khác gói GB |
| [Thordata](https://www.thordata.com/) | SERP, scraper, browser | Cần báo giá riêng với proxy network |
| [Floppydata](https://floppydata.com/) | Cloud browser, scraping API, proxy | Cần chốt đơn vị của headline trước tính |

<a id="benchmark"></a>
## 🔬 Cách thử provider trước khi mua lớn

1. Chọn workload được phép; cố định URL, country, request size và tiêu chí dữ liệu hợp lệ.
2. Thử cùng khung giờ và cùng concurrency; ghi cả cold start lẫn phiên dài.
3. Đo p50/p95 latency, timeout, HTTP status, nội dung thực và chi phí dashboard.
4. Kiểm tra ASN, country thực, DNS/WebRTC và đổi IP trong sticky session.
5. Chạy lặp ở nhiều thời điểm; không dùng một trang demo để kết luận toàn bộ pool.
6. Chỉ mua lớn khi chi phí/kết quả và hỗ trợ đáp ứng nhu cầu.

Mẫu lưu kết quả: [BENCHMARK.md](BENCHMARK.md). Các trường hợp chưa có dữ liệu phải ghi `not measured`, không điền tỷ lệ quảng cáo của hãng.

<a id="methodology"></a>
## 📚 Phương pháp, nguồn và đóng góp

Lấy cảm hứng về phạm vi từ [TheGP/Proxy-Providers-List](https://github.com/TheGP/Proxy-Providers-List). Bản NDT viết lại cấu trúc và phân tích, không sao chép nhận xét hoặc coi bảng giá gốc là nguồn hiện hành. Mọi link provider đi trực tiếp, không thêm referral, mã giới thiệu hay redirect affiliate.

Các mốc giá có nguồn chính thức tại dòng tương ứng. Danh bạ mở rộng là hàng chờ nghiên cứu, không được gắn nhãn “đã xác minh giá”. Thông tin tài liệu do hãng công bố không chứng minh chất lượng hoặc nguồn IP; lỗi HTTP cũng không chứng minh provider đã chết. Xem [nguồn và giới hạn](SOURCES.md), [cách đóng góp](CONTRIBUTING.md), [nhật ký](CHANGELOG.md).

<div align="center">
<strong>Bộ tài nguyên NDT</strong><br>
<a href="https://github.com/nguyenduytan/NDT-Antidetect-Tools">🕵️ Antidetect Tools</a> · <a href="https://github.com/nguyenduytan/NDT-Captcha-Solver-Services">🧩 Captcha Solver Services</a><br>
<sub>Dùng cho nghiên cứu, QA và tác vụ có quyền truy cập hợp lệ.</sub>
</div>
