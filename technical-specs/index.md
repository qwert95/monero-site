---
layout: custom
title: titles.technicalspecs
permalink: /technical-specs/index.html
---
<div class="about-monero">
    <section class="container">
        <div class="row">
            <!-- left two-thirds block-->
            <div class="full col-xs-12">
                <div class="info-block text-adapt">
                    <div class="row">
                        <div class="col">
                            <h3>No premine, no instamine, no token</h3>
                        </div>
                    </div>
                    <div>
                        <ul>
                            <li>Monero had no premine or instamine</li>
                            <li>Monero did not sell any token</li>
                            <li>Monero had no presale of any kind</li>
                        </ul>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Proof of Work</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>CryptoNight</li>
                            <li>may change in the future</li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Difficulty retarget</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>every block</li>
                            <li>based on the last 720 blocks, excluding 20% of the timestamp outliers</li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Block time</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>2 minutes</li>
                            <li>may change in the future as long as emission curve is preserved</li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Block reward</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>smoothly decreasing and subject to penalties for blocks greater than median size of the last 100 blocks (M100)</li>
                            <li>see the <a href="https://moneroblocks.info/">latest block</a> coinbase transaction amount for current reward</li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Block size</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>dynamic, maximum of 2 * M100</li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Emission curve</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>first, main curve: ~18.132 million coins by the end of May 2022</li>
                            <li>then, tail curve: 0.6 XMR per 2-minute block, kicks in once main emission is done, translates to <1% inflation decreasing over time</li>
                            <li>see <a href="https://www.reddit.com/r/Monero/comments/512kwh/useful_for_learning_about_monero_coin_emission/">charts and details</a></li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Max supply</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>infinite</li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Sender privacy</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>Ring signatures</li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Recipient privacy</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>Stealth addresses</li>
                        </ol>
                    </div>
                    <div class="row">
                        <div class="col">
                            <h3>Amount obfuscation</h3>
                        </div>
                    </div>
                    <div>
                        <ol>
                            <li>Ring confidential transactions</li>
                        </ol>
                    </div>
                </div>
            </div>
            <!-- end right one-third block-->
        </div>
    </section>
</div>
