# Manjyo
<!doctype html>
<html lang="ko">

<head>

<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-T54JG94');</script>
<!-- End Google Tag Manager -->

	<meta charset="UTF-8">
	<meta name="viewport" content="user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, width=device-width">
	<title>[##_page_title_##]</title>
	<link rel="alternate" type="application/rss+xml" title="[##_title_##]" href="[##_rss_url_##]" />

	<link rel="stylesheet" href="./style.css">
	<link rel="stylesheet" href="./images/font.css">
	<style>
		<s_if_var_cover-image>
		.wrap_sub {
			background-image: url('[##_var_cover-image_##]');
		}
		</s_if_var_cover-image>
	</style>

	<!--[if lt IE 9]>
	<script src="//t1.daumcdn.net/tistory_admin/lib/jquery/jquery-1.12.4.min.js"></script>
	<![endif]-->
	<!--[if gte IE 9]><!-->
	<script src="//t1.daumcdn.net/tistory_admin/lib/jquery/jquery-3.5.1.min.js" integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin="anonymous"></script>
	<!--<![endif]-->
</head>

<body id="[##_body_id_##]">

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-T54JG94"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

<s_t3>

	<div id="dkIndex">
		<!--웹접근성용 바로가기 링크 모음-->
		<a href="#dkBody">본문 바로가기</a>
	</div>
	<div id="dkWrap" class="wrap_skin">
		<!-- 카테고리버튼 클릭시 'navi_on' 클래스 부여 -->
		<div id="dkHead" role="banner" class="area_head">
			<h1 class="screen_out">[##_title_##]</h1>
			<button type="button" class="btn_cate">
				<span class="ico_skin ico_cate">카테고리</span>
			</button>
			<div class="area_search ">
				<button type="button" class="btn_search">
					<span class="ico_skin ico_search">검색하기</span>
				</button>
				<s_search>
					<form action="#" method="get" class="frm_search box_search" onsubmit="[##_search_onclick_submit_##]">
						<fieldset>
							<legend class="screen_out">검색하기</legend>
							<label for="[##_search_name_##]" class="lab_search screen_out">블로그 내 검색</label>
							<input type="text" name="[##_search_name_##]" id="[##_search_name_##]" class="tf_search" placeholder="Search" value="[##_search_text_##]" data-value="[##_search_text_##]">
							<span class="ico_skin ico_search"></span>
						</fieldset>
					</form>
				</s_search>
			</div>
			<div class="area_profile">
				<div class="tit_post">
					<a href="/" class="link_post">[##_title_##]</a>
				</div>
				<span class="thumb_profile">
                <img src="[##_image_##]" class="img_profile" alt="프로필사진">
            </span>
				<span class="txt_profile">[##_blogger_##]</span>
			</div>
		</div>
		<hr class="hide">
		<div id="dkContent" class="cont_skin" role="main">
			<div id="cMain">
				<div id="mFeature" class="wrap_sub">
					<div class="cont_sub">
						<div class="inner_sub">
							<div class="area_sub">
								<div role="navigation" class="area_navi">
									[##_category_list_##]
									<a href="[##_guestbook_link_##]" class="link_guestbook">Guestbook</a>
								</div>
								<div class="wrap_etc">
									<div class="col_aside left_side">
										<s_sidebar>
											<s_sidebar_element>
												<!-- 공지사항 -->
												<s_rct_notice>
													<div class="box_aside">
														<strong class="tit_aside">Notice</strong>
														<ul class="list_board">
															<s_rct_notice_rep>
																<li><a href="[##_notice_rep_link_##]" class="link_board">[##_notice_rep_title_##]</a></li>
															</s_rct_notice_rep>
														</ul>
													</div>
												</s_rct_notice>
											</s_sidebar_element>

											<s_sidebar_element>
												<!-- 최근에 올라온 글 -->
												<div class="box_aside">
													<strong class="tit_aside">Recent Posts</strong>
													<ul class="list_board">
														<s_rctps_rep>
															<li><a href="[##_rctps_rep_link_##]" class="link_board">[##_rctps_rep_title_##]</a></li>
														</s_rctps_rep>
													</ul>
												</div>
											</s_sidebar_element>

											<s_sidebar_element>
												<!-- 최근에 달린 댓글 -->
												<div class="box_aside">
													<strong class="tit_aside">Recent Comments</strong>
													<ul class="list_board">
														<s_rctrp_rep>
															<li><a href="[##_rctrp_rep_link_##]" class="link_board">[##_rctrp_rep_desc_##]</a></li>
														</s_rctrp_rep>
													</ul>
												</div>
											</s_sidebar_element>

											<s_sidebar_element>
												<!-- 링크 -->
												<div class="box_aside">
													<strong class="tit_aside">Link</strong>
													<ul class="list_board">
														<s_link_rep>
															<li><a href="[##_link_url_##]" class="link_board" target="_blank">[##_link_site_##]</a></li>
														</s_link_rep>
													</ul>
												</div>
											</s_sidebar_element>
										</s_sidebar>
									</div>


									<div class="col_aside right_side">
										<s_sidebar>
											<s_sidebar_element>
												<!-- 달력 -->
												<div class="box_aside box_calendar">
													[##_calendar_##]
												</div>
											</s_sidebar_element>

											<s_sidebar_element>
												<!-- 태그 클라우드 -->
												<div class="box_aside box_tag">
													<strong class="tit_aside">Tags</strong>
													<ul class="list_tag">
														<s_random_tags>
															<li><a href="[##_tag_link_##]" class="link_tag [##_tag_class_##]">[##_tag_name_##]</a></li>
														</s_random_tags>
													</ul>
													<a href="[##_taglog_link_##]" class="link_more">more</a>
												</div>
											</s_sidebar_element>

											<s_sidebar_element>
												<!-- 글 보관함 -->
												<div class="box_aside box_archive">
													<strong class="tit_aside">Archives</strong>
													<ul class="list_keep">
														<s_archive_rep>
															<li><a href="[##_archive_rep_link_##]" class="link_keep">[##_archive_rep_date_##]</a> ([##_archive_rep_count_##])</li>
														</s_archive_rep>
													</ul>
												</div>
											</s_sidebar_element>

											<s_sidebar_element>
												<!-- 방문자수 -->
												<div class="box_aside box_visitor">
													<dl class="list_visitor">
														<dt>Today</dt>
														<dd>[##_count_today_##]</dd>
													</dl>
													<dl class="list_total">
														<dt>Total</dt>
														<dd>[##_count_total_##]</dd>
													</dl>
												</div>
											</s_sidebar_element>
										</s_sidebar>
									</div>
								</div>
							</div>
						</div>
						<button type="button" class="ico_skin btn_close">닫기</button>

						<strong class="screen_out">관리 메뉴</strong>
						<ul class="list_control">
							<li><a href="[##_owner_url_##]/entry/post" class="ico_skin link_write" title="글쓰기">글쓰기</a></li>
							<li><a href="[##_guestbook_link_##]" class="ico_skin link_memo" title="방명록">방명록</a></li>
							<li><a href="[##_rss_url_##]" class="ico_skin link_rss" title="RSS">RSS</a></li>
							<li><a href="[##_owner_url_##]" class="ico_skin link_manage" title="관리">관리</a></li>
						</ul>
					</div>
				</div>

				<div id="mArticle" class="article_skin">

					<s_list>
						<div class="list_title">
							<h2 id="dkBody" class="tit_skin"><span class="screen_out">목록</span><span class="txt_title">[##_list_conform_##] ([##_list_count_##])</span></h2>
						</div>
					</s_list>

					<div class="index_title">
						<h2 class="tit_skin"><span class="txt_title">[##_title_##]</span></h2>
					</div>

					<s_article_rep>
						<s_index_article_rep>
							<div class="list_content">
								<s_article_rep_thumbnail>
									<a href="[##_article_rep_link_##]" class="thumbnail_post"><img src="//i1.daumcdn.net/thumb/C150x150/?fname=[##_article_rep_thumbnail_raw_url_##]"></a>
								</s_article_rep_thumbnail>
								<a href="[##_article_rep_link_##]" class="link_post">
									<strong class="tit_post ">[##_article_rep_title_##]</strong>
									<p class="txt_post">[##_article_rep_summary_##]</p>
								</a>
								<div class="detail_info">
									<a href="[##_article_rep_category_link_##]" class="link_cate">[##_article_rep_category_##]</a>
									<span class="txt_bar"></span>
									<span class="txt_date">[##_article_rep_date_##]</span>
								</div>
							</div>
						</s_index_article_rep>


						<s_permalink_article_rep>
							<h2 id="dkBody" class="screen_out">[##_article_rep_title_##] 본문</h2>
							<div class="area_title">
								<strong class="tit_category"><a href="[##_article_rep_category_link_##]">[##_article_rep_category_##]</a></strong>
								<h3 class="tit_post">[##_article_rep_title_##]</h3>
								<span class="info_post">[##_article_rep_author_##]
                                <span class="txt_bar"></span>[##_article_rep_date_##]
								<s_ad_div>
									<span class="txt_bar"></span><a href="[##_s_ad_m_link_##]" class="link_detail">수정</a>
									<span class="txt_bar"></span><a href="#" onclick="[##_s_ad_s2_onclick_##]" class="link_detail">[##_s_ad_s1_label_##]</a>
									<span class="txt_bar"></span><a href="#" onclick="[##_s_ad_d_onclick_##]" class="link_detail">삭제</a>
								</s_ad_div>
							</span>
							</div>

							<div class="area_view">
								[##_article_rep_desc_##]
							</div>
							<div class="area_etc">
								<s_tag_label>
									<dl class="list_tag">
										<dt>Tag</dt>
										<dd>[##_tag_label_rep_##]</dd>
									</dl>
								</s_tag_label>
							</div>

							<s_article_related>
								<div class="area_related">
									<strong class="tit_related">'[##_article_rep_category_##]' Related Articles</strong>
									<ul class="list_related">
										<s_article_related_rep>
											<li class="[##_article_related_rep_type_##]">
												<a href="[##_article_related_rep_link_##]" class="link_related">
													<s_article_related_rep_thumbnail>
													<span class="thumb_related">
														<img src="//i1.daumcdn.net/thumb/C185x200/?fname=[##_article_related_rep_thumbnail_link_##]" class="img_related" alt="">
													</span>
													</s_article_related_rep_thumbnail>
													<span class="txt_related">[##_article_related_rep_title_##]</span>
													<span class="date_related">[##_article_related_rep_date_##]</span>
													<span class="frame_related"></span>
												</a>
											</li>
										</s_article_related_rep>
									</ul>
									<a href="[##_article_rep_category_link_##]" class="link_more">more</a>
								</div>
							</s_article_related>

							<div class="area_reply">
								<s_rp>
									[##_comment_group_##]
								</s_rp>
							</div>


						</s_permalink_article_rep>
					</s_article_rep>

					<s_page_rep>
						<s_permalink_article_rep>
							<h2 id="dkBody" class="screen_out">[##_article_rep_title_##] 본문</h2>
							<div class="area_title">
								<h3 class="tit_post">[##_article_rep_title_##]</h3>
							</div>

							<div class="area_view">
								[##_article_rep_desc_##]
							</div>
						</s_permalink_article_rep>
					</s_page_rep>

					<s_notice_rep>
						<s_index_article_rep>
							<div class="list_content">
								<a href="[##_notice_rep_link_##]" class="link_post">
									<strong class="tit_post ">[##_notice_rep_title_##]</strong>
									<p class="txt_post">[##_notice_rep_summary_##]</p>
								</a>
								<div class="detail_info">
									<a href="/notice" class="link_cate">공지사항</a>
									<span class="txt_bar"></span> [##_notice_rep_date_##]
								</div>
							</div>
						</s_index_article_rep>

						<s_permalink_article_rep>
							<h2 id="dkBody" class="screen_out">[##_notice_rep_title_##] 본문</h2>
							<div class="area_title">
								<strong class="tit_category"><a href="/notice">공지사항</a></strong>
								<h3 class="tit_post">[##_notice_rep_title_##]</h3>
								<span class="info_post">[##_notice_rep_author_##]
                                <span class="txt_bar"></span>[##_notice_rep_date_##]</span>
							</div>

							<div class="area_view">
								[##_notice_rep_desc_##]
							</div>
						</s_permalink_article_rep>
					</s_notice_rep>

					<s_article_protected>
						<s_index_article_rep>
							<div class="list_content">
								<a href="[##_article_rep_link_##]" class="link_post">
									<strong class="tit_post ">[##_article_rep_title_##]</strong>
									<p class="txt_post">보호되어 있는 글입니다.</p>
								</a>
								<div class="detail_info">
									<a href="[##_article_rep_category_link_##]" class="link_cate">[##_article_rep_category_##]</a>
									<span class="txt_bar"></span> [##_article_rep_date_##]
								</div>
							</div>
						</s_index_article_rep>

						<s_permalink_article_rep>
							<h2 id="dkBody" class="screen_out">[##_article_rep_title_##] 본문</h2>
							<div class="area_title">
								<strong class="tit_category"><a href="[##_article_rep_category_link_##]">[##_article_rep_category_##]</a></strong>
								<h3 class="tit_post">[##_article_rep_title_##]</h3>
								<span class="info_post">[##_article_rep_author_##]
                                <span class="txt_bar"></span>[##_article_rep_date_##]</span>
							</div>

							<form class="protected_form" onsubmit="[##_article_dissolve_##]">
								<p>보호되어 있는 글입니다.<br>내용을 보시려면 비밀번호를 입력하세요.</p>
								<input type="password" id="[##_article_password_##]" name="[##_article_password_##]" value="" placeholder="비밀번호" />
								<button type="submit">확인</button>
							</form>
						</s_permalink_article_rep>
					</s_article_protected>

					<s_tag>
						<h2 id="dkBody" class="tit_skin"><span class="txt_title">Tags</span></h2>
						<ul class="list_tag">
							<s_tag_rep>
								<li><a href="[##_tag_link_##]" class="link_tag [##_tag_class_##]">[##_tag_name_##]</a></li>
							</s_tag_rep>
						</ul>
					</s_tag>

					<s_guest>
						[##_guestbook_group_##]
					</s_guest>

					<s_paging>
						<div class="area_paging">
    					<span class="inner_paging">
                <a [##_prev_page_##] class="btn_prev [##_no_more_prev_##]">
									<span class="ico_skin ico_prev">
										<span class="screen_out">
                      이전
                    </span>
									</span>
									Prev
								</a>
    						<s_paging_rep>
    							<a [##_paging_rep_link_##] class="link_page">[##_paging_rep_link_num_##]</a>
    						</s_paging_rep>
                <a [##_next_page_##] class="btn_next [##_no_more_next_##]">
									Next
									<span class="ico_skin ico_next">
										<span class="screen_out">
                      다음
                    </span>
									</span>
								</a>
    					</span>
						</div>
					</s_paging>
				</div>
			</div>
		</div>
		<hr class="hide">
		<div id="dkFoot" role="contentinfo" class="area_foot">
			<small class="info_copyright">
				Blog is powered by
				<a href="http://www.kakaocorp.com" class="emph_t" target="_blank">kakao</a> / Designed by
				<a href="http://www.tistory.com" class="emph_t" target="_blank">Tistory</a>
			</small>
		</div>
	</div>


</s_t3>
<script src="./images/script.js"></script>
</body>

</html>
