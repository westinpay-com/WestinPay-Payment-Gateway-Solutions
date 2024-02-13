<img class="w-75" src="https://i.ibb.co/2KbqLG2/Westin-Pay.png" alt="image">

       <section id="setting-two">
                                    <p>Request to the end point with the following parameters below.</p>
                                    <div class="table-responsive">
                                        <table class="table table-bordered">
                                            <thead>
                                                <tr>
                                                    <th>Param Name</th>
                                                    <th>Param Type</th>
                                                    <th>Description</th>
                                                </tr>
                                            </thead>
                                            <tbody>
                                                <tr>
                                                    <td>public_key</td>
                                                    <td>string (50)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Your Public API key                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>identifier</td>
                                                    <td>string (20)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Identifier is basically for identify payment at your end                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>currency</td>
                                                    <td>string (4)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Currency Code, Must be in Upper Case. e.g. USD,EUR                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>amount</td>
                                                    <td>decimal</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Payment amount.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>details</td>
                                                    <td>string (100)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Details of your payment or transaction.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>ipn_url</td>
                                                    <td>string</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        The url of instant payment notification.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>success_url</td>
                                                    <td>string</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Payment success redirect url.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>cancel_url</td>
                                                    <td>string</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Payment cancel redirect url.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>site_logo</td>
                                                    <td>string/url</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Your business site logo.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>checkout_theme</td>
                                                    <td>string</td>
                                                    <td>
                                                        <span class="badge badge--info font-size--12px">Optional</span>
                                                        Checkout form theme dark/light. Default theme is light                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>customer_name</td>
                                                    <td>string (30)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Customer name.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>customer_email</td>
                                                    <td>string (30)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Customer valid email.                                                    </td>
                                                </tr>
                                            </tbody>
                                        </table>
                                    </div><!-- table-responsive end -->

                                </section>

                                    </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
